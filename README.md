# Dashboard Monitoring Perekrutan CRO

Static HTML (`index.html`) + Vercel Function (`api/sheet.js`) yang menarik data dari Google Sheets LOGBOOK CRO.

## Deploy
1. Push folder ini ke GitHub.
2. Vercel -> Add New Project -> import repo -> Framework: **Other** -> Deploy.
3. Pastikan Google Sheet: Share -> **Anyone with the link: Viewer**.

## Catatan
- Nama tab di sheet harus sama dengan nama cabang (BALIKPAPAN, SAMARINDA, dst.), atau isi GID di pengaturan sinkronisasi.
- Ganti sheet: set Environment Variable `SHEET_ID` di Vercel.
