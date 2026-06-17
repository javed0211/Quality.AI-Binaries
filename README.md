# Quality.AI — Windows installers

Pre-built Windows packages for **Quality.AI** (Electron desktop app).

## Recommended: Portable (no Setup.exe)

If the NSIS installer leaves an empty folder (only an uninstaller), skip the Setup.exe entirely.

| Version | File | Notes |
|---------|------|-------|
| **0.1.20** | [0.1.20/Local-Portable.zip](0.1.20/Local-Portable.zip) | **Use this on x64 PCs** — extract all files, run `QualityAI.exe` |

**Steps:** Extract the zip to e.g. `%LOCALAPPDATA%\Programs\QualityAI`, then run `QualityAI.exe`. See `README.txt` inside the zip.

## NSIS Setup (optional)

| Version | File | Variant | Notes |
|---------|------|---------|-------|
| 0.1.20 | [0.1.20/Local.zip](0.1.20/Local.zip) | Bundled local MongoDB | x64 — may fail on some PCs; prefer Local-Portable |
| 0.1.19 | [0.1.19/Local.zip](0.1.19/Local.zip) | Bundled local MongoDB | x64 — may leave only uninstaller |
| 0.1.18 | [0.1.18/Local.zip](0.1.18/Local.zip) | Bundled local MongoDB | x64 — broken shortcuts on upgrade |
| 0.1.17 | [0.1.17/Local.zip](0.1.17/Local.zip) | Bundled local MongoDB | ARM64 only — do not use on x64 PCs |

Each Local.zip contains `Quality.AI Setup <version> (Local).exe`.

**Install location (when Setup works):** `%LOCALAPPDATA%\Programs\QualityAI\QualityAI.exe` (shortcut name: **Quality.AI**)

Built from [test-agent-nexus](https://github.com/javed0211/test-agent-nexus) at commit `154df7ae` (portable bundle for v0.1.20).
