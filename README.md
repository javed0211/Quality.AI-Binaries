# Quality.AI — Windows installers

Pre-built Windows packages for **Quality.AI** (Electron desktop app).

## Recommended: Portable (no Setup.exe)

If the NSIS installer leaves an empty folder (only an uninstaller), skip the Setup.exe entirely.

| Version | File | Notes |
|---------|------|-------|
| **0.1.22** | [0.1.22/Local-Portable.zip](0.1.22/Local-Portable.zip) | **Latest** — x64, fast API startup, default admin user |
| 0.1.21 | [0.1.21/Local-Portable.zip](0.1.21/Local-Portable.zip) | x64 portable |
| 0.1.20 | [0.1.20/Local-Portable.zip](0.1.20/Local-Portable.zip) | x64 portable |

**Steps:** Extract the zip to e.g. `%LOCALAPPDATA%\Programs\QualityAI`, then run `QualityAI.exe`. See `README.txt` inside the zip.

**Default login (first install):** `admin@quality.ai` / `QualityAI@Admin1`

## NSIS Setup (optional)

| Version | File | Variant | Notes |
|---------|------|---------|-------|
| 0.1.22 | [0.1.22/Local.zip](0.1.22/Local.zip) | Bundled local MongoDB | x64 — may fail on some PCs; prefer Local-Portable |
| 0.1.21 | [0.1.21/Local.zip](0.1.21/Local.zip) | Bundled local MongoDB | x64 |
| 0.1.20 | [0.1.20/Local.zip](0.1.20/Local.zip) | Bundled local MongoDB | x64 |

Each Local.zip contains `Quality.AI Setup <version> (Local).exe`.

**Install location (when Setup works):** `%LOCALAPPDATA%\Programs\QualityAI\QualityAI.exe` (shortcut name: **Quality.AI**)

Built from [test-agent-nexus](https://github.com/javed0211/test-agent-nexus) at commit `7b7572d7` (v0.1.22).
