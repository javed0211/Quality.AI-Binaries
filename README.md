# Quality.AI — Windows installers

Pre-built Windows NSIS installers for **Quality.AI** (Electron desktop app).

| Version | File | Variant | Notes |
|---------|------|---------|-------|
| **0.1.20** | [0.1.20/Local.zip](0.1.20/Local.zip) | Bundled local MongoDB — **latest** | **x64** — installs to `Programs\QualityAI` (no dot); fresh app ID |
| 0.1.19 | [0.1.19/Local.zip](0.1.19/Local.zip) | Bundled local MongoDB | x64 — may leave only uninstaller; use 0.1.20+ |
| 0.1.18 | [0.1.18/Local.zip](0.1.18/Local.zip) | Bundled local MongoDB | x64 — broken shortcuts on upgrade |
| 0.1.17 | [0.1.17/Local.zip](0.1.17/Local.zip) | Bundled local MongoDB | ARM64 only |
| 0.1.16 | [0.1.16/Cloud.zip](0.1.16/Cloud.zip) | MongoDB Atlas (cloud) | |
| 0.1.16 | [0.1.16/Local.zip](0.1.16/Local.zip) | Bundled local MongoDB | |

Each zip contains `Quality.AI Setup <version> (Local).exe`. Extract and run the setup to install.

**Install location:** `%LOCALAPPDATA%\Programs\QualityAI\QualityAI.exe` (shortcut name: **Quality.AI**)

Built from [test-agent-nexus](https://github.com/javed0211/test-agent-nexus) at commit `cc555466` (v0.1.20).
