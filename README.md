# Quality.AI — Windows installers

Pre-built Windows packages for **Quality.AI** (Electron desktop app).

## Latest: 0.1.25 (GitHub Release)

Because this repo exceeded its **Git LFS budget**, new builds are published as **[Release assets](https://github.com/javed0211/Quality.AI-Binaries/releases/tag/v0.1.25)** (not under version folders).

**Download:** https://github.com/javed0211/Quality.AI-Binaries/releases/tag/v0.1.25

| File | Variant | CPU | Notes |
|------|---------|-----|-------|
| **Local-x64-Portable.zip** | Local | **x64** | **Recommended for standard PCs** |
| **Local-arm64-Portable.zip** | Local | **ARM64** | Windows on ARM only |
| Local-x64.zip / Local-arm64.zip | Local | x64 / ARM64 | NSIS Setup.exe inside |
| Cloud-x64-Portable.zip / Cloud-arm64-Portable.zip | Cloud (Atlas) | x64 / ARM64 | Portable |
| Cloud-x64.zip / Cloud-arm64.zip | Cloud (Atlas) | x64 / ARM64 | NSIS Setup.exe inside |

**Portable steps:** Extract to e.g. `%LOCALAPPDATA%\Programs\QualityAI`, then run `QualityAI.exe`.

**Default login (first install):** `admin@quality.ai` / `QualityAI@Admin1`

Built from [test-agent-nexus](https://github.com/javed0211/test-agent-nexus) at commit `b31c6b74` (v0.1.25).

## Older versions (LFS folders)

Folders `0.1.15`–`0.1.24` remain for historical downloads. Prefer the release above for the newest build.