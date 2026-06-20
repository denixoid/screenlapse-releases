# Veduta — releases

Public hosting for [Veduta](https://github.com/denixoid/screenshot-taker)'s auto-update
feed and downloads. Served at **https://denixoid.github.io/veduta-releases/** via GitHub
Pages.

- `appcast.xml` — the Sparkle update feed the app checks (`SUFeedURL`).
- `Veduta-*.zip` — notarized release builds.
- `index.html` — a small landing page.

Releases are produced by `scripts/release.sh` in the app repo; copy the resulting
`releases/Veduta-<version>.zip` and `releases/appcast.xml` here and push.
