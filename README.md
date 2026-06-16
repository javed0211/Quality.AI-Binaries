# Quality.AI — Windows installers

Pre-built Windows NSIS installers for **Quality.AI** (Electron desktop app).

| Version | File | Variant | Notes |
|---------|------|---------|-------|
| **0.1.18** | [0.1.18/Local.zip](0.1.18/Local.zip) | Bundled local MongoDB — **latest** | **x64** (standard Windows PCs) |
| 0.1.17 | [0.1.17/Local.zip](0.1.17/Local.zip) | Bundled local MongoDB | ARM64 only — do not use on x64 PCs |
| 0.1.16 | [0.1.16/Cloud.zip](0.1.16/Cloud.zip) | MongoDB Atlas (cloud) | |
| 0.1.16 | [0.1.16/Local.zip](0.1.16/Local.zip) | Bundled local MongoDB | |
| 0.1.15 | [0.1.15/Cloud.zip](0.1.15/Cloud.zip) | MongoDB Atlas (cloud) | |
| 0.1.15 | [0.1.15/Local.zip](0.1.15/Local.zip) | Bundled local MongoDB | |

Each zip contains `Quality.AI Setup <version> (Cloud|Local).exe` (older builds may use `Nexus AI Setup`). Extract and run the setup to install.

Install location: `%LOCALAPPDATA%\Programs\Quality.AI\Quality.AI.exe`

Built from [test-agent-nexus](https://github.com/javed0211/test-agent-nexus) at commit `9a8dc8c9` (v0.1.18).
