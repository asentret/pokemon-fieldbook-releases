# Pokemon Fieldbook v1.7.0

2026-10-11 (Windows only)

Windows **1.7.0** · Android **1.6.13**

## Changes

- Added Windows 10 64-bit support alongside Windows 11. Installer minimum
  is now Windows 10 build 10240 instead of Windows 11 build 22000.
- Windows 10 uses its standard native title bar; the lavender/purple app
  theme, menus, light/dark modes and collection features remain available.
- Windows 11 retains its custom themed title bar.
- Started the 1.7 series. Future versions roll from X.Y.9 to X.(Y+1).0
  instead of X.Y.10. Existing historical version numbers are retained.
- Android remains 1.6.13; collection backup format 1 is unchanged.
- Preserved the previous source, executable and runtime under
  backups/desktop-1.6.12-before-1.7.0 before editing.
- Windows 11 launch/installer tests and simulated Windows 10 fallback
  checks are run for this release; a real Windows 10 test is still pending.

## Installation and backups

Run the Windows installer over your existing installation, or extract the full portable ZIP. Collection saves are retained. Android users can install the compatible APK over the existing app. Checklist and HOME format-1 backups remain compatible.

## Update checks

The desktop app uses the official GitHub feed by default. Startup checks are enabled unless you previously disabled them. Custom feed URLs and disabled startup checks are preserved. You can check manually or change these preferences in Settings > Check for updates. Downloads open in your browser; installation stays manual. Android does not have an in-app update checker.

The release feed and referenced installers must be published together for online checks to work. No collection data is uploaded.
