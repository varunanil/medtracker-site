# medtracker-site

Static site for https://medtracker.varunanil.dev, served by GitHub Pages.

- `.well-known/assetlinks.json` lets the Med Tracker apps open follow links (Android App Links): `dev.varun.medtracker` (release upload key) and `dev.varun.medtracker.dev` (the debug key of the machine that builds dev APKs).
- `delete-account.html` is the account-deletion page Google Play asks for: the in-app steps, the request email, what is deleted and what is kept (decision 0006 in the app repo). Linked from `index.html`.
- `404.html` is shown for every other path, including `/i/<code>` and `/dev/i/<code>`: it explains the link, offers "Open in Med Tracker", and prints the code for typing in.
- Nothing secret lives here; certificate fingerprints are readable from any APK.
