# MINO downloads

MINO is a free, local-first Windows notes app with an edge deck, folders, calendar, checklists and reminders.

This repository contains **release downloads only**, not the application source or personal note data.

## Download

Open [Releases](https://github.com/ishivam06/MINO-releases/releases/latest) and choose the Windows x64 setup or portable EXE.

- Setup: installs for the current Windows user.
- Portable: quit MINO before replacing the executable at its existing location.
- Keep your vault and encryption key. Replacing the application is not erasing notes.
- Make a password-protected backup before upgrading from development builds.

## Updates

Version 1.0.2.0 and newer use this public release feed. Earlier builds need one manual upgrade. MINO checks every 15 days while running; manual checking is in Settings → About & updates. Checking does not send notes and can be disabled.

Release `.sig` files are free cryptographic updater signatures. **The EXEs are not Windows Authenticode-signed**; updater signatures do not establish a trusted Windows publisher or SmartScreen reputation. Do not disable Windows security to install.

Full installed-app update/restart, clean-machine WebView2 setup and multi-monitor/DPI behavior have not yet been validated end-to-end for this release. Read each release's verification notes before installing.

Private signing keys, GitHub credentials, vaults and encrypted drafts must never be uploaded here.
