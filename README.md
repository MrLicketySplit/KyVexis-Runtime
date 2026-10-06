# KyVexis Runtime

Prebuilt Node.js binaries for the [KyVexis-MDBH](https://github.com/MrLicketySplit/KyVexis-MDBH) Android app.

Self-contained `node` executables built for Android (bionic), gzipped for download. Each release's `manifest.json` pins SHA-256 hashes — the app verifies before installing.

Upstream build source: [Delusions6515/node-android-build](https://github.com/Delusions6515/node-android-build) (official Node.js + Termux patches, `--partly-static`, no Termux runtime deps).
