# Quality.AI â€” Windows installers

Pre-built Windows packages for **Quality.AI** (Electron desktop app).

## Recommended: Portable (no Setup.exe)

If the NSIS installer leaves an empty folder (only an uninstaller), skip the Setup.exe entirely.

| Version | File | CPU | Notes |
|---------|------|-----|-------|
| **0.1.24** | [0.1.24/Local-x64-Portable.zip](0.1.24/Local-x64-Portable.zip) | **x64** | **Latest for standard PCs** â€” CI-built, arch-validated backend |
| **0.1.24** | [0.1.24/Local-arm64-Portable.zip](0.1.24/Local-arm64-Portable.zip) | **ARM64** | Windows on ARM only |
| 0.1.22 | [0.1.22/Local-Portable.zip](0.1.22/Local-Portable.zip) | x64 | **Do not use** â€” backend may be wrong CPU arch |

**Steps:** Extract the zip to e.g. `%LOCALAPPDATA%\Programs\QualityAI`, then run `QualityAI.exe`. See `README.txt` inside the zip.

**Default login (first install):** `admin@quality.ai` / `QualityAI@Admin1`

## NSIS Setup (optional)

| Version | File | CPU | Notes |
|---------|------|-----|-------|
| 0.1.24 | [0.1.24/Local-x64.zip](0.1.24/Local-x64.zip) | x64 | Prefer Local-x64-Portable |
| 0.1.24 | [0.1.24/Local-arm64.zip](0.1.24/Local-arm64.zip) | ARM64 | Windows on ARM only |
| 0.1.22 | [0.1.22/Local.zip](0.1.22/Local.zip) | x64 | Unreliable â€” use 0.1.24 Local-x64 |

Each `Local-*.zip` contains `Quality.AI Setup <version> (Local-<arch>).exe`.

**Install location (when Setup works):** `%LOCALAPPDATA%\Programs\QualityAI\QualityAI.exe` (shortcut name: **Quality.AI**)

Built from [test-agent-nexus](https://github.com/javed0211/test-agent-nexus) at commit `cef09d25` (v0.1.24).
