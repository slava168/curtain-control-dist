# curtain-control-dist

Public update feed for **Curtain Control** (macOS menu-bar app).

Contains only the self-update artifacts — no source:

- `dist/version.json` — latest version + download URL
- `dist/CurtainControl.zip` — the prebuilt app bundle (contains no credentials)

The app source lives in a separate (private) repo. Installed copies check
`dist/version.json` here and update themselves.
