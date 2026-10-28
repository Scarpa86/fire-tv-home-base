# Home Base for Fire TV

A cleaner Fire TV home screen with live scores for your teams, your favorite apps in a dock, and quick shortcuts.

## What you need

- A Fire TV stick or Fire TV that runs Fire OS. Newer Vega OS devices can't install it.
- A **Windows computer on the same Wi-Fi**, used once for about 2 minutes. Fire TV only lets a computer switch on the Home button part.

## Downloads

| | |
|---|---|
| **Downloader code** (on the TV) | **8188054** |
| **[Setup-Fire-TV.bat](https://github.com/Scarpa86/fire-tv-home-base/releases/latest/download/Setup-Fire-TV.bat)** | One click: installs Home Base, links the Home button, turns off Amazon ads & bloat |
| **[Undo-Fire-TV.bat](https://github.com/Scarpa86/fire-tv-home-base/releases/latest/download/Undo-Fire-TV.bat)** | One click: puts the TV completely back to normal |

## Set up (step by step)

**On the TV**

1. Turn on Developer Options if you don't see it: **Settings > My Fire TV > About**, highlight the TV's name and press **OK 7 times**.
2. **Settings > My Fire TV > Developer Options > ADB debugging > ON.**
3. *Optional, to install from the TV:* get **Downloader** from the app store, turn on **Developer Options > Install unknown apps > Downloader**, open Downloader, type **8188054**, choose **Go** and then **Install**. Home Base opens with these same steps on screen. (The computer tool installs it anyway, so you can skip this.)

**On the Windows computer**

4. Download **[Setup-Fire-TV.bat](https://github.com/Scarpa86/fire-tv-home-base/releases/latest/download/Setup-Fire-TV.bat)**. If the browser warns about the file, choose **Keep**.
5. Double-click it. If Windows shows *"Windows protected your PC"*, click **More info > Run anyway**.
6. It finds the TV by itself. If you have more than one TV, it asks which one: the number is on Home Base's setup screen, or under **Settings > My Fire TV > About > Network**.

**Back on the TV**

7. When the TV asks **"Allow USB debugging?"**, tick **Always allow from this computer** and choose **OK**.
8. Wait for **ALL DONE** on the computer. Home Base opens on the TV and the Home button now goes to it.
9. Pick your teams: **League > (first letter) > Team**, up to 4.

## Using it

- **Team cards:** press OK to watch. Hold OK (or press the Menu button) to change, move or remove a team, or to pick its watch app.
- **Remote Buttons** (bottom of the screen): choose what the remote's app buttons do, like Prime Video or Netflix. By default they work normally.
- **Shortcuts** (scroll down): settings, all apps, screen dimmer, and **Setup & Undo**.

## Undo everything

Double-click **[Undo-Fire-TV.bat](https://github.com/Scarpa86/fire-tv-home-base/releases/latest/download/Undo-Fire-TV.bat)** on the computer. It turns Amazon's apps back on, resets menu speed, unlinks the Home button, uninstalls Home Base and turns ADB debugging back off.
(No computer? On the TV, **Shortcuts > Setup & Undo > Undo everything** uninstalls Home Base, but it can't turn Amazon's apps back on.)
