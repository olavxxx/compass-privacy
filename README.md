# Nordkompass privacy site

Public GitHub Pages source for the Nordkompass privacy policy.

**Live:** <https://olavxxx.github.io/compass-privacy/>

Pages is deployed from `main` / root. Verified live on 2026-10-28 (HTTP 200, contact
`olavamjelde@gmail.com`, English and Norwegian sections present).

## Updating

`index.html` is the same file as `android-compass/store/privacy-policy.html`. When the policy changes:

1. Edit `android-compass/store/privacy-policy.html` and bump its date.
2. Copy it over `index.html` here.
3. Commit and push both repositories. Pages redeploys from `main` automatically.

Do not add analytics, external fonts, or scripts: the point of the page is the same as the app's —
nothing leaves the device.
