SHRI SHYAAM LIBRARY PRO — INSTALLATION

This package is an installable Progressive Web App (PWA), not a native App Store IPA/APK. It is designed for iPhone Safari and can be added to the Home Screen for an app-like experience.

PUBLISH FREE WITH GITHUB PAGES
1. Create a new GitHub repository (for example shyaam-library-pro).
2. Upload ALL files from this ZIP into the repository root: index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png.
3. In the repository, open Settings → Pages. Choose Deploy from a branch, select main and /(root), then Save.
4. Wait for GitHub Pages to publish. Open the published https://YOUR-USERNAME.github.io/REPOSITORY/ link in Safari on your iPhone.
5. Tap Share → Add to Home Screen → Add. Open the new Home Screen icon.

FIRST ADMIN PIN: 1234. Change it immediately in Settings.

FEATURES
- Admin-only local PIN gate (no student login)
- Student records, seats, attendance, fee payments and printable receipts
- Edit each student’s monthly fee for a selected month from Fees → Edit fee; month-specific changes do not alter other months
- Change default Day, Day-Night and Night plan rates in Settings → Fee structure
- Locker assignment and release
- Multi-student WhatsApp message composer with fee reminder and greeting templates
- Custom library name, phone and address
- JSON backup/restore and CSV student export
- Optional Supabase cloud sync setup is present in Settings; requires your own Supabase project and configuration

IMPORTANT DATA NOTES
- Local records are stored in the browser on this device. Do not clear Safari website data unless you have a backup.
- Download a JSON backup regularly and store it somewhere safe.
- WhatsApp opens a pre-filled message; you must review and press Send in WhatsApp. Bulk messages are opened one at a time with confirmation.
- The PIN is a convenience lock, not server-grade authentication.
- A PWA cannot be installed directly as a native iOS IPA without Apple's signing/distribution process. GitHub Pages hosting and Home Screen installation are free.
