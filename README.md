# Flynt

**A local, offline-capable agentic coding station — an [Arcus Foundry](https://arcusfoundry.com) release.**

This repository hosts the official **Flynt installer** downloads. The latest signed-by-hash
build is always published under [**Releases**](https://github.com/Arcusfoundry/flynt-releases/releases).

## Download

1. Go to the [latest release](https://github.com/Arcusfoundry/flynt-releases/releases/latest).
2. Download **`FlyntSetup.exe`**.
3. Verify the download against the published SHA256 (see below), then run it.

## Verify your download

Each release lists the SHA256 of `FlyntSetup.exe` in its notes. Confirm it matches before running:

```powershell
Get-FileHash .\FlyntSetup.exe -Algorithm SHA256
```

The printed hash must equal the one in the release notes. If it does not match, **do not run the
installer** — re-download from the official release page above.

The current version, download, and its SHA256 always live on the
[**latest release**](https://github.com/Arcusfoundry/flynt-releases/releases/latest) page — that is
the single source of truth, so this README never goes stale.

---

© Arcus Foundry. The Flynt source is maintained privately; this repository distributes the
built installer only.
