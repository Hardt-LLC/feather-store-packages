# Feather Task Manager: Microsoft Store packages

This repository only hosts the signed installers that the Microsoft Store downloads for [Feather Task Manager](https://github.com/Hardt-LLC/FeatherTaskManager). The Store needs a direct HTTPS link without redirects, which GitHub release downloads do not provide.

Every file here is a byte-for-byte copy of an asset from the matching [GitHub release](https://github.com/Hardt-LLC/FeatherTaskManager/releases), signed by **HARDT** (Azure Artifact Signing) and timestamped. Files are added once per version and never replaced; the Store links pin the commit SHA.

| Version | Installer | SHA-256 |
| --- | --- | --- |
| 2026.9.4 | [FeatherTaskManager-2026.9.4-Setup-x64.exe](2026.9.4/FeatherTaskManager-2026.9.4-Setup-x64.exe) | see [SHA256SUMS.txt](2026.9.4/SHA256SUMS.txt) |

To download Feather yourself, use the [latest release](https://github.com/Hardt-LLC/FeatherTaskManager/releases/latest). Source code, license and security policy live in the main repository.
