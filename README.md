# The Human Respiratory System: 3D PWA
Developed by Mateen Yousuf, Teacher. For Classes 5–6. No backend, no API key, works offline.

Files: index.html (all content, CSS, JS) · three.min.js (local Three.js r149) · manifest.json · service-worker.js · offline.html · icons/

## Run / test
Service workers need **HTTPS or localhost** (file:// shows the app but not offline/install).
    cd resp_pwa && python3 -m http.server 8080   # open http://localhost:8080

## Deploy
Upload the whole folder to any static HTTPS host (GitHub Pages, Netlify, Cloudflare Pages, school server).

## Install on Android
Open the URL in Chrome while online → tap **Install App** (or menu ⋮ → Install app). iPhone/iPad Safari: Share → Add to Home Screen.

## Verify offline
Open once online, reload once, then switch on airplane mode (or DevTools → Network → Offline) and reload. The Online/Offline chip shows the state.

## Updating
Bump `VERSION` in service-worker.js after editing any file; users get an "update available" toast.

Models are simplified for learning; breathing numbers are illustrative; not medical advice.
