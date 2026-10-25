# floorp-go drops

Public mirror of floorp-go release artifacts and update metadata.

This repository exists so the in-app "Check for updates" feature can fetch
`version.json` without authentication — the main repo (`floorp-go`) is private.

## Contents

- `version.json` — latest version metadata (fetched by the app).
- `floorp-go-<version>-<abi>-release.apk` — release APKs, one per ABI.

## Updating

When a new floorp-go release ships, copy the per-ABI APKs here, update
`version.json`, and push. GitHub Pages serves both.
