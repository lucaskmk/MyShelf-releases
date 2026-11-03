# MyShelf

Local-first notes, boards and study. Your notebooks are plain Markdown files in a
folder you choose — they open in any editor, sync with OneDrive or any other
service, and keep working offline.

> The interface is in Portuguese (pt-BR).

This repository only hosts the installers and the update feed. The source code is
private.

## What it does

- **Pages and notebooks** in Markdown, with subpages, columns, tables, callouts,
  toggles, images and links between pages.
- **Free board** (espaço livre): cards, images, drawing, arrows and trails you can
  walk through and turn into text.
- **Study**: spaced repetition (FSRS) and daily recall built from your own notes.
- **Import** from Notion, OneNote (`.onepkg` / `.one`), Word, PDF, PowerPoint,
  Markdown and HTML.
- **Password-protected notebooks and pages**, encrypted on disk (AES-256), with a
  recovery key.
- **Daily backup** of the whole folder to a `.zip` in a location you choose.

## Download

Get the latest version from [Releases](../../releases/latest).

| System | File |
|---|---|
| Windows | `MyShelf_x.y.z_x64-setup.exe` |
| macOS (Intel and Apple Silicon) | `.dmg` |
| Linux | `.AppImage`, `.deb` or `.rpm` |

The app updates itself: when a new version is out it shows a notice, and installs
only when you click.

### First run

The installers are not code-signed yet, so the system warns on the first run:

- **Windows** — "Windows protected your PC": click *More info* → *Run anyway*.
  Some antivirus programs flag unsigned new apps; if yours quarantines MyShelf,
  restore it from the quarantine.
- **macOS** — right-click the app → *Open* (or System Settings → Privacy &
  Security → *Open Anyway*). If it says the app is damaged, run
  `xattr -cr /Applications/MyShelf.app` in Terminal.
- **Linux** — for the AppImage, `chmod +x` and run it.

## Your data

- Everything stays in the folder you pick. There is no account and no server.
- The app goes online only to check for updates (this repository) and, if you set
  up an AI provider with your own key, to talk to that provider.
- Keep a backup: turn on the daily backup in *Configurações → cadernos & pasta*,
  pointing to another disk, a USB drive or a cloud folder.
- If you lose both the password **and** the recovery key of a protected notebook,
  its content cannot be recovered — by anyone.

## License

© 2026 Lucas Kamikawa. All rights reserved — see [LICENSE](LICENSE).
