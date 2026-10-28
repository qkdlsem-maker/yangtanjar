# Install and use Yangtanjar

[한국어](INSTALL.ko.md) · [Home](../README.md)

## Install

1. Open the [v0.4.11-beta.1 release](https://github.com/qkdlsem-maker/yangtanjar/releases/tag/v0.4.11-beta.1).
2. Download **Yangtanjar-0.4.11-Setup-x64.exe** from Assets. GitHub's automatically generated **Source code** archives contain these repository documents, not the runnable app.
3. Run the installer. Choose English or Korean for the setup screens.
4. Open Yangtanjar from the Start menu.

Windows 10 version 2004 or later / Windows 11 x64 and .NET Framework 4.8 or later are required. The app installs for the current user without requesting administrator access. ARM64 and 32-bit Windows are not validated targets for this beta.

The file is not digitally signed. A Windows publisher or reputation warning may appear. Do not disable Windows protection to install it. Cancel if you are unsure about the download. The release includes `SHA256SUMS.txt` to compare the file with the published copy; a matching hash is not a security certification.

## Language

On first launch, Korean Windows uses Korean; other Windows languages use English. At the top right of settings, select **English**, **한국어**, or **자동 / System**, choose **Quit app**, and reopen the app. The language selection is saved. Changing the language does not reset your rug or rename your saved designs. The Windows file picker and standard dialog buttons may follow the Windows language.

## Open settings and quit

Right-click the rug and select **Designs and settings**, or double-click the rug icon in the system tray (it may be inside the hidden-icons menu). Closing settings leaves the desktop rug running. Use **Quit app** or the tray menu's **Quit** to stop it.

Hold **Alt** to interact with icons underneath. Use **Shift + drag** to move the whole rug and **Ctrl + mouse wheel** to resize it. The ordinary mouse wheel rotates it. **Ctrl + Alt + Shift + R** hides or shows it; **Ctrl + Alt + Backspace** centers and unfolds it.

## Your designs

**Add image** accepts PNG, JPEG and BMP. Crop away fringe or background already baked into the image; the app draws its own adjustable fringe. Images must be no larger than 100 MB or 80 megapixels, with an aspect ratio between 1:3 and 3:1.

**Design studio** combines patterns, colors, borders and freehand drawing. **Save and use as rug** adds the result to My designs. **Export PNG** exports the rug body without the separately drawn fringe.

Expand **Backups and recovery** to back up designs and drafts, restore a `.yrbackup` file, or continue an autosaved draft. A backup can include original imported images, drawings and settings. Keep it private. The most recent edits since the last successful autosave can be lost after an unexpected shutdown.

## Update or uninstall

Make a design backup, then run the new installer. It asks the running app to save or keep your work and close safely. If you cancel, or the app cannot close safely, installation stops. Very old versions may need to be closed manually. Run one rug version at a time.

Uninstall through **Windows Settings → Apps → Installed apps** (or **Apps & features**). User-created designs, settings and drafts remain after uninstalling. The installer does not enable automatic startup, change your wallpaper or move desktop files.

## Locations

| Content | Folder |
| --- | --- |
| App | `%LOCALAPPDATA%\Programs\Yangtanjar4` |
| Settings, drafts, recovery backups | `%LOCALAPPDATA%\Yangtanjar\DesktopRug4` |
| Personal designs and original images | `%LOCALAPPDATA%\Yangtanjar\RugLibrary` |

Support: [GitHub issue forms](https://github.com/qkdlsem-maker/yangtanjar/issues/new/choose). Reports are public. Share only the relevant part of an error log after removing private paths; do not attach your whole backup or settings folder.
