# Release checksums

The SHA256 checksum of every file attached to a [release](https://github.com/bridgepatcher/PatcherSupportPkg/releases),
recorded automatically by a GitHub Actions workflow when the file is uploaded.

Checksums are only ever **added** to this file, never changed or removed. If a file on a
release is replaced later, its first checksum stays here and the new one is added below
it with a warning. The file's git history shows when each checksum was recorded, which a
replaced file can't change. `SHA256SUMS` on a release, in comparison, is regenerated
whenever the release's files change.

## How to check a download

On macOS, in Terminal:

```sh
shasum -a 256 ~/Downloads/<file>
```

The output must match the checksum listed below for that release and file. If it
doesn't, or if the file is marked as changed below and you didn't expect that, don't
open it and [report it](https://github.com/bridgepatcher/PatcherSupportPkg/security/advisories/new).

To check every file of a release at once, copy its lines into a file named `sums.txt`
next to the downloads and run `shasum -a 256 -c sums.txt`.

<!-- releases (newest first) -->

<!-- release: 2.6 -->
## 2.6

[Release page](https://github.com/bridgepatcher/PatcherSupportPkg/releases/tag/2.6) · published 2026-11-08

Recorded 2026-11-15 00:18 EET (UTC+2):

```
c59d30a6a5bbe1be847c7a7fb9bbcb5eca6c76008f6bb36ac1c77eaca2802605  Universal-Binaries.dmg
```
