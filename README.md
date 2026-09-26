# Netrunner Nexus — downloads

Netrunner Nexus is a Windows desktop browser based on Chromium, built around
local control and a customizable interface.

## Download

Open [Releases](../../releases) and download the Windows x64 setup file. Each
release includes a `.sha256` file for integrity checks. In PowerShell, compare
the expected hash with:

```powershell
Get-FileHash .\NetrunnerNexus-Setup-<version>-win-x64.exe -Algorithm SHA256
```

Run the installer to install for the current Windows user. It does not require
administrator access. Remove the app from **Settings → Installed apps**.

## Preview status

Version 0.4.0 Preview 1 includes the Windows sandbox, local privacy controls,
integrated downloads, a per-profile password vault protected by Windows DPAPI,
full fingerprint-protection coverage (canvas, WebGL, AudioContext, fonts,
hardware/timezone), and an automatic update service that verifies both a
SHA-256 hash and a digital signature before installing anything. Windows Hello
on Windows 11 is required to reveal, edit, or delete saved passwords.
Automatic sign-in and password filling are not available yet.

The installer is unsigned, so Windows may show an unknown publisher warning.
Check the published SHA-256 file before installing.

## Licensing

Original Netrunner Nexus code, branding, and assets are proprietary. The
installer grants end users permission to install and run an unmodified official
release for their own use; it does not grant source-code or redistribution
rights. The installer contains the CEF license and Chromium third-party credits.
See [LICENSE](LICENSE) and [third-party notices](THIRD_PARTY_NOTICES.md).

The application source code is maintained in a separate private repository.
