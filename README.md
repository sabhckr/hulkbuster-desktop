# HULKBUSTER desktop

Installers for the HULKBUSTER desktop app on macOS, Windows and Linux. This repository holds
releases only; it contains no source code.

**[Download the latest release](https://github.com/sabhckr/hulkbuster-desktop/releases/latest)**

| System | File |
| --- | --- |
| macOS, Apple silicon | `HULKBUSTER-mac-arm64.dmg` |
| macOS, Intel | `HULKBUSTER-mac-x64.dmg` |
| Windows 10 and 11, 64-bit | `HULKBUSTER-windows-x64-setup.exe` |
| Linux, 64-bit | `HULKBUSTER-linux-x86_64.AppImage` |

The app shows your HULKBUSTER workspace in its own window. It loads the HULKBUSTER service, so it
always matches the web version and needs an internet connection.

## First launch

- **macOS:** open the DMG and drag HULKBUSTER to Applications. The app is not notarized by Apple
  yet, so macOS blocks the first launch: open System Settings, Privacy & Security, and choose
  **Open Anyway**.
- **Windows:** run the setup file. The installer is not code-signed yet, so SmartScreen may warn:
  choose **More info**, then **Run anyway**.
- **Linux:** make the AppImage executable (`chmod +x HULKBUSTER-linux-x86_64.AppImage`) and run it.

Each release lists SHA-256 checksums in `SHA256SUMS`. Check a download with
`shasum -a 256 -c SHA256SUMS` (macOS and Linux) or `Get-FileHash` (Windows PowerShell).
