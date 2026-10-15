# MINO downloads

MINO is a free, local-first notes app for Windows and macOS, with an edge deck, folders, calendar, checklists and reminders.

This repository contains **release downloads only**, not the application source or personal note data.

## Windows downloads

Open [Windows releases](https://github.com/ishivam06/MINO-releases/releases/latest) and choose the Windows x64 setup or portable EXE.

- Setup: installs for the current Windows user.
- Portable: quit MINO before replacing the executable at its existing location.
- Keep your vault and encryption key. Replacing the application is not erasing notes.
- Make a password-protected backup before upgrading from development builds.

## macOS download — v1

Download [MINO-v1-macOS-universal.dmg](https://github.com/ishivam06/MINO-releases/releases/download/v1/MINO-v1-macOS-universal.dmg) or read the [Mac v1 release notes](https://github.com/ishivam06/MINO-releases/releases/tag/v1).

- One universal build for Apple Silicon and Intel; minimum configured macOS version: 13.3.
- Quit MINO before replacing the app in Applications. Retain your existing vault and keys.
- The Mac release label is `v1`; the internal application version is `1.0.0`.
- The app is ad-hoc signed, not Apple Developer ID signed or notarized. Gatekeeper may restrict a downloaded build; keep macOS security enabled.
- This Mac build uses manual installation. No authenticated Mac updater payload is published, and the Windows shared update feed is unchanged.

## Windows updates

The Windows update feed currently serves **v1.0.0** (Windows file version 1.0.0.0). Earlier internal releases were withdrawn before public distribution. The separate Mac `v1` release does not replace the Windows release or its update metadata.

MINO checks this public release feed every 15 days while running; manual checking is in Settings → About & updates. Checking does not send notes and can be disabled. Future updates must use a higher version than 1.0.0.

Release `.sig` files are free cryptographic updater signatures. **The EXEs are not Windows Authenticode-signed**; updater signatures do not establish a trusted Windows publisher or SmartScreen reputation. Do not disable Windows security to install.

Full installed-app update/restart, clean-machine WebView2 setup and multi-monitor/DPI behavior have not yet been validated end-to-end for this release. Read each release's verification notes before installing.

Private signing keys, GitHub credentials, vaults and encrypted drafts must never be uploaded here.
