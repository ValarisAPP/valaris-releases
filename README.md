<p align="center">
  <a href="https://valaris.app"><img src="https://valaris.app/logo.png" width="96" alt="Valaris"></a>
</p>

<h1 align="center">Valaris for Windows — releases</h1>

<p align="center">All the world's AI in one chat. Hundreds of models through OpenRouter, voice, photos, PDFs and video.<br>
<a href="https://valaris.app"><b>valaris.app</b></a> · <a href="https://valaris.app/security.html">Security and privacy</a> · <a href="mailto:support@valaris.app">support@valaris.app</a></p>

---

This repository lists **every version of the Valaris installer for Windows** with its SHA-256 checksum and
release notes. The program's source code is not published here.

## Download

- The newest installer: **[valaris.app](https://valaris.app)** → “Download for Windows”.
- All versions: the **[Releases](https://github.com/ValarisAPP/valaris-releases/releases)** page of this repository.

The installed program updates itself; every update is checked with our signature before it is installed.

## Check the file you downloaded

Every release lists the SHA-256 of its installer. In PowerShell:

```powershell
Get-FileHash .\ValarisAPP-Setup-1.6.0.exe
```

The `Hash` value must be exactly the one in the release notes. If it is different, do not run the file and
write to support@valaris.app.

## Security and privacy in short

- **Your data stays on your device.** The OpenRouter key is kept in Windows Credential Manager; chats, files and
  settings are in the app's data folder. There is no account and no server with your chats.
- **Addresses the app contacts:** `openrouter.ai` (answers, models, balance, sign-in), `valaris.app` (new version
  check and short notices), web pages only when a model reads a link from your chat (public addresses only), and
  `artificialanalysis.ai` only if you add your own key for model ratings. No analytics, no ads, no telemetry.
- **Signed updates.** Version, file name, size and SHA-256 of every installer are signed with our Ed25519 key; the
  app throws away anything that does not match.
- **Folders.** The app reads only folders you connect; every change to a file asks you first and can be undone.
- **No administrator rights** are needed to install or run Valaris.

Details: <https://valaris.app/security.html>

## Why an antivirus may warn

Valaris is a new program and is not yet signed with a paid code-signing certificate. Some antiviruses use machine
learning that is suspicious of new, little-known programs. For example, Microsoft Defender may show
`Trojan:Win32/Wacatac.B!ml` — the `!ml` ending means a guess of the machine-learning model, not a known virus.
We report such false positives to the antivirus makers. Download Valaris only from valaris.app or from this page,
and compare the SHA-256.

## Report a vulnerability

See [SECURITY.md](SECURITY.md).

---

© 2026 ValarisAPP · 6 Marjanishvili street, Tbilisi, Georgia ·
[Terms](https://valaris.app/terms.html) · [Privacy](https://valaris.app/privacy.html)
