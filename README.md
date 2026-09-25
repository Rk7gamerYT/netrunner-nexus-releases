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

Version 0.2.0 Preview 1 is an early preview. Some privacy and security features
are still in development, and the Windows sandbox is disabled in this build.
Do not use this version for sensitive browsing.

## Licensing

Original Netrunner Nexus code, branding, and assets are proprietary. The
installer grants end users permission to install and run an unmodified official
release for their own use; it does not grant source-code or redistribution
rights. The installer contains the CEF license and Chromium third-party credits.
See [LICENSE](LICENSE) and [third-party notices](THIRD_PARTY_NOTICES.md).

The application source code is maintained in a separate private repository.
