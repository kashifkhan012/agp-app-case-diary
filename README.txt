AGP–APP CASE DIARY — STARTER PWA

What is included
- index.html: mobile-friendly case diary app
- manifest.json: installable-app metadata
- service-worker.js: basic offline app-shell cache

Current features
- Add/edit/delete cases
- Add/edit/delete hearing diary entries
- Track payment claims and mark payments paid
- Add/edit/delete tasks and compliance follow-ups
- Dashboard and search
- JSON export and restore backup
- Browser-local storage

Important limitations
- This is a starter prototype, not a production-ready legal-record system.
- Data stays in the current browser/device. It does not sync across devices.
- No login, server backup, encryption, shared access, or automatic push reminders are implemented.
- Before real client/case data is entered, a security and backup plan should be agreed and tested.
- For reliable Android installation, serve these files over HTTPS. A file opened directly from Downloads will not have full PWA installation/offline behaviour.

Phone-only next step
1. Upload the contents of this folder to an HTTPS static hosting service (for example, GitHub Pages or Netlify).
2. Open the resulting HTTPS address in Chrome on Android.
3. Use Chrome menu > Install app or Add to Home screen.

No hosting has been configured by this package; no public URL is included.
