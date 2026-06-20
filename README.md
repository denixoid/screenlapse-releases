# Screenlapse — releases

Public hosting for [Screenlapse](https://github.com/denixoid/screenshot-taker)'s auto-update
feed and downloads. Served at **https://screenlapse.net/** via GitHub
Pages.

- `appcast.xml` — the Sparkle update feed the app checks (`SUFeedURL`).
- `Screenlapse-*.zip` — notarized release builds.
- `index.html` — a small landing page.

Releases are produced by `scripts/release.sh` in the app repo; copy the resulting
`releases/Screenlapse-<version>.zip` and `releases/appcast.xml` here and push.
