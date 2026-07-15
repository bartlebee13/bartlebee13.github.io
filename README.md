# bartlebee13.github.io

Hosts Android **Digital Asset Links** for the **blurt** app, so `https://bartlebee13.github.io/blurt/…` links open the app directly (App Links) instead of a browser.

- `.well-known/assetlinks.json` — the verification file (package `com.blurt.blurt` + signing-cert SHA-256).
- `.nojekyll` — so GitHub Pages serves the `.well-known/` folder.

If the APK's signing key changes, add the new cert SHA-256 to the `sha256_cert_fingerprints` array.
