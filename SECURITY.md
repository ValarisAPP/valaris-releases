# Security policy

## Reporting a vulnerability

Please write to **support@valaris.app** with the subject **“Security”**. Describe what you found, how to repeat
it and which version of Valaris you used (Settings → About).

- We reply within a few business days and keep you informed until it is fixed.
- Please do not publish the details before a fixed version is released.
- Do not access other people's data and do not disrupt our services while testing.

## Supported versions

Only the newest version receives fixes. The installed program updates itself; you can also download the newest
installer from [valaris.app](https://valaris.app).

## How releases are protected

- Every installer is described by its version, file name, size and SHA-256, and this description is signed with
  our Ed25519 key. The app installs an update only when the signature, size and checksum match.
- Each release on this page lists the SHA-256 of its installer, so you can check a downloaded file:
  `Get-FileHash .\ValarisAPP-Setup-<version>.exe` in PowerShell.
- Builds are checked automatically for leaked data (databases, logs, keys, licence codes, tokens) before release.

More: <https://valaris.app/security.html>
