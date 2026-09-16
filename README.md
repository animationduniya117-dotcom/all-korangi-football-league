# ALL KORANGI FOOTBALL LEAGUE — Real Registration System

Features:
- Persistent registrations in `server/data/players.json`
- Player photo uploads in `server/uploads/`
- Admin login
- Search players
- Delete players
- Printable registration cards
- Dashboard totals

Install:
```powershell
npm install
npm run install-all
```
If PowerShell blocks npm scripts:
```powershell
npm.cmd install
npm.cmd run install-all
```

Start:
```powershell
npm run dev
```

Open:
- Public registration: http://localhost:5173/
- Admin panel: http://localhost:5173/admin

Default local admin:
- Username: `admin`
- Password: `AKFL@2026`

For an online production site, change credentials and use proper hosted authentication/database/storage.
