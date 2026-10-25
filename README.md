# MailFlow Lite — Windows Release

Standalone Windows 10/11 desktop application for local, permission-gated email
workspaces. This repository holds **release binaries only** — no source code.

## Download

Grab `MailFlowLite_Windows_Release.zip` from the
[Releases page](../../releases).

## Install (Windows 10 / 11, 64-bit)

1. Download `MailFlowLite_Windows_Release.zip`.
2. Right-click the ZIP → **Extract All…** into a permanent folder such as
   `C:\Users\<you>\Apps\MailFlowLite` (do not run it from inside the ZIP window).
3. Double-click `MailFlowLite.exe`. No Python installation is required.

Full instructions: `INSTALL.txt` inside the ZIP.

## Verify your download

```
sha256sum -c SHA256SUMS.txt
```

Expected SHA-256 values are listed in `SHA256SUMS.txt` at the repository root
and in the release notes.

## Notes

- The executable is **unsigned**, so Windows SmartScreen may show a publisher
  warning on first run. Choose *More info → Run anyway* only after checking the
  SHA-256 above — or build from source yourself.
- Gmail sending requires a one-time OAuth setup with your own Google account;
  see `docs/GOOGLE_SETUP.md` in the source project. No credentials, tokens or
  contact data are bundled.
- Application data is stored locally in `%LOCALAPPDATA%\MailFlowLite`.

## License

MIT — see `LICENSE`. Third-party notices: `THIRD_PARTY_NOTICES.md`.