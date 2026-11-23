# Eclipse OS

A home screen for Google TV / Android TV. Nothing on the TV is deleted, and there is a kill switch to go back to the normal Google TV home at any time.

**Download:** [EclipseOS.apk (latest)](https://github.com/wracksz/eclipse-os/releases/latest/download/EclipseOS.apk)

## 1. Install the app

1. On the TV, install **Downloader** (by AFTVnews) from the Google Play Store.
2. Open Downloader and enter the Eclipse OS code (or this link):
   `https://github.com/wracksz/eclipse-os/releases/latest/download/EclipseOS.apk`
3. When Android asks, allow Downloader to **install unknown apps**, then choose **Install**.
4. Open **Eclipse OS** from the TV's apps list.

## 2. Make it the home screen

Eclipse opens a **Home Screen Setup** page the first time. Choose **Full Replace & Debloat**:

1. Press **Turn on debugging** and follow the steps:
   Settings → System → About → click **Android TV OS build** 7 times, then
   Settings → System → Developer options → turn on **USB debugging**.
2. Come back and press **Full Replace**.
3. The TV asks **"Allow debugging?"** — tick **Always allow**, then **Allow**.
4. Done: the Home button now opens Eclipse OS.

The checklist shows each app that will be switched off and what you lose. Apps are only switched off, never uninstalled.

**Important trade-off:** Full Replace has to switch off the *Google TV setup service*, because it otherwise takes the Home button back. On many TVs this also stops **casting from a phone** (Chromecast). If you rely on casting, don't use Full Replace — use **Other ways to set Home** in Launcher Settings instead.

## 3. Going back (kill switch)

Launcher Settings → **Kill switch: back to Google TV**.
This turns the Google TV home (and everything Eclipse switched off) back on and gives it the Home button. Eclipse stays installed as a normal app; remove it from Settings → Apps if you want.

If debugging was turned off since, the kill switch shows the exact Settings screen to press **Enable** by hand.

## Tips

- Hold **OK** on any app for options: favorite, move, rename, hide, categories, uninstall.
- **Launcher Settings** (red button, top right) = Eclipse's own options. **Android** (grey button) = the TV's normal settings.

## Tested on

TCL Google TV (Android 12). Other brands (Sony, Hisense, Philips, Chromecast with Google TV) should work but haven't been tested yet.

Inter typeface © 2020 The Inter Project Authors, SIL Open Font License 1.1.
