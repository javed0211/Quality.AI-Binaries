# Quality.AI — Windows installers

Pre-built Windows packages for **Quality.AI** (Electron desktop app).

## Recommended: Portable (no Setup.exe)

If the NSIS installer leaves an empty folder (only an uninstaller), skip the Setup.exe entirely.

| Version | File | CPU | Notes |
|---------|------|-----|-------|
| **0.1.24** | [0.1.24/Local-arm64-Portable.zip](0.1.24/Local-arm64-Portable.zip) | **ARM64** | Windows on ARM — arch-validated backend |
| **0.1.24** | `0.1.24/Local-x64-Portable.zip` | **x64** | **Building via CI** — for standard PCs like schitre's |
| 0.1.22 | [0.1.22/Local-Portable.zip](0.1.22/Local-Portable.zip) | x64 | Do not use — backend may be wrong arch |

**Steps:** Extract the zip to e.g. `%LOCALAPPDATA%\Programs\QualityAI`, then run `QualityAI.exe`. See `README.txt` inside the zip.

**Default login (first install):** `admin@quality.ai` / `QualityAI@Admin1`

## NSIS Setup (optional)

| Version | File | CPU | Notes |
|---------|------|-----|-------|
| 0.1.24 | [0.1.24/Local-arm64.zip](0.1.24/Local-arm64.zip) | ARM64 | Windows on ARM only |
| 0.1.24 | `0.1.24/Local-x64.zip` | x64 | Building via CI |
| 0.1.22 | [0.1.22/Local.zip](0.1.22/Local.zip) | x64 | Unreliable — use 0.1.24 Local-x64 when published |

Each `Local-*.zip` contains `Quality.AI Setup <version> (Local-<arch>).exe`.

**Install location (when Setup works):** `%LOCALAPPDATA%\Programs\QualityAI\QualityAI.exe` (shortcut name: **Quality.AI**)

Built from [test-agent-nexus](https://github.com/javed0211/test-agent-nexus) at commit `d75fdf8a` (v0.1.24).
