# AceleCore Agent — releases

This repository holds **released builds only**, no source code.

- `version.txt` — the version the installed agents should run. Agents check it every 6 hours.
- **Releases** — one `AceleCoreAgent.exe` per version, tag `vX.Y.Z`.

**Releasing a version (in this order):**
1. Create the release `vX.Y.Z` here and attach `AceleCoreAgent.exe` (tested first!).
2. Only then change `version.txt` to `X.Y.Z`.

Changing `version.txt` installs that version on every agent PC.
