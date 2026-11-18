# medtracker-site

Static site for https://medtracker.varunanil.dev, served by GitHub Pages.

- `.well-known/assetlinks.json` lets the Med Tracker apps open follow links (Android App Links): `dev.varun.medtracker` (release upload key) and `dev.varun.medtracker.dev` (the debug key of the machine that builds dev APKs).
- `404.html` is shown for every other path, including `/i/<code>` and `/dev/i/<code>`: it explains the link, offers "Open in Med Tracker", and prints the code for typing in.
- Nothing secret lives here; certificate fingerprints are readable from any APK.
