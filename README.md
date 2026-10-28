# Home Base for Fire TV

A cleaner Fire TV home screen with live scores for your teams, a customizable app dock and shortcuts.
Setup happens on the Fire TV itself. No computer needed.

## Downloader code: **8188054**

Type **8188054** into the Downloader app. Or type the full link:

```
https://github.com/Scarpa86/fire-tv-home-base/releases/latest/download/HomeBase.apk
```

Both always point to the newest version.

## Install on a Fire TV Stick (about 3 minutes)

1. Install **Downloader** (by AFTVnews) from the Fire TV app store.
2. Turn on Developer Options if you don't see it: **Settings > My Fire TV > About**, then press OK on the device name 7 times.
3. In **Settings > My Fire TV > Developer Options**:
   - **Install unknown apps > Downloader**: ON
   - **ADB debugging**: ON
4. Open Downloader, type **8188054**, press **Go**, then **Install**. Choose **Open** when it finishes.
5. Home Base opens its setup screen. Press **Start setup**. When the TV asks *"Allow USB debugging?"*, tick **Always allow** and choose **OK**. The rest happens by itself:
   - the Home button now opens Home Base
   - Amazon ads, bloat and tracking are turned off, and menus are sped up (untick that box before Start if you don't want this)
6. Press **Back** and pick your teams: League > (first letter) > Team. You can follow up to 4.

## Changing teams later

Highlight a team card and hold **OK** (or press the Menu button) to change the team, move it left or right, remove it, or choose its watch app.
The dashed **Add team** card adds another one.

## Undo everything

**Home Base > Shortcuts > Setup & Undo > Undo everything.**
This turns the Amazon apps back on, resets menu speed, unlinks the Home button, turns ADB debugging back off and uninstalls Home Base. The Fire TV goes back to normal.
ADB debugging has to still be on for the undo to work.

## Notes

- Works on Fire TV devices running Fire OS (Android-based). It won't work on the newer Vega OS sticks.
- To update, install a newer version the same way. Your teams and layout are kept.
