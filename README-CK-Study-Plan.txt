CK SIR — 2026 O/L LAST MONTH STUDY PLAN
======================================

FILES
- ck-ol-study-plan.html : the study planner app
- manifest.webmanifest : installable web-app metadata
- sw.js : offline cache service worker

QUICK START
1. Open ck-ol-study-plan.html in Chrome/Edge to use it.
2. Register a profile with name, PIN ID and password.
3. Set your 9 subject names and difficulty groups in My Subjects.
4. Use the Study Timer to record focused sessions. One completed 60-minute timer earns 1 hour in your history. The Star Loop can also be marked manually.
5. Export your progress JSON regularly as a backup.

INSTALL AS AN APP
For the Install App / offline PWA features, the files must be hosted on HTTPS (or localhost).
Upload all three files to a static HTTPS host (for example, GitHub Pages or Netlify), then open the hosted URL in Chrome and choose Install app / Add to Home Screen.
Opening the HTML directly as a file still allows the planner to work, but browsers do not allow service workers/PWA installation from file://.

IMPORTANT ACCOUNT LIMIT
This starter version stores profiles and progress in this browser's local storage. The same PIN/password will work again on this device/browser. It does NOT sync accounts between different devices, and local storage is not secure authentication. Cross-device login requires a real backend (e.g. Firebase/Supabase), HTTPS hosting, server-side password hashing, and secure profile/image storage. Do not reuse an important password here.

PLAN BASIS
The uploaded CK Sir PDF defines 4 tracks × 30 hours = 120 hours, 1 star per hour, 3 days per track (Day A/B/C), 36 mini-infinity recalls, and memory locks at D04, D11, D18, D25. Subject names and daily distribution are customizable in this app.
