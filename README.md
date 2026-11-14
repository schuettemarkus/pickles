# Pickles

An editable King's Court points leaderboard for an 8-player pickleball weekend. It's one self-contained `index.html`.

**Live site:** https://schuettemarkus.github.io/pickles/

## Shared scores (Firebase)
Scores live in a free Firebase Realtime Database, which the page reaches through Firebase's REST API with no SDK. Taps are sent as server-side increments, so phones tapping at the same time never overwrite each other, and changes stream to every open phone instantly.

Setup: create a Realtime Database in a free Firebase project and set these rules:

```json
{ "rules": { "pickles": { ".read": true, ".write": true } } }
```

The database URL is set in `FIREBASE_URL` in `index.html` (currently `https://pickles-d0e25-default-rtdb.firebaseio.com`). Anyone who opens the site can change points.

## Hosting
GitHub Pages, deployed by `.github/workflows/pages.yml` on every push. In Settings → Pages, Source must be set to **GitHub Actions**.
