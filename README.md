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
- **Shortcuts** (scroll down; press Down again for **More Shortcuts**): settings, all apps, screen dimmer, Find Apps, Phone Remote, Ad Blocker, and **Setup & Undo**.
- **Rearrange:** hold OK (or press Menu) on any shortcut or dock app, choose **Move**, then use the arrows to carry it anywhere, onto the other shortcut page too. Press **OK** to drop it.
- **Find Apps** (bottom of the screen): opens the Appstore to search for and download apps.
- **Help** (bottom of the screen): something not working? Describe it and press Send. It goes straight to the developer, with your TV's model and Home Base version so the problem can be fixed.
- **Check for Updates** (bottom of the screen): turns green when a new version is out.

Home Base checks in once a day with a random ID for the TV, its model and the Fire OS / Home Base versions, so the developer can see how many TVs use it. No names, accounts or viewing history are sent.

## Ad Blocker

The setup tool turns it on: the TV uses AdGuard's ad-blocking DNS, so ads and trackers inside apps and websites don't load. Switch it on or off any time at **More Shortcuts > Ad Blocker**. If an app or a sign-in page won't load, turn it off.
It can't block ads inside YouTube, Prime Video, Hulu and similar video, because those come from the same servers as the shows. (Run Setup-Fire-TV.bat once with 2.9 or newer to enable the switch.)

## Phone Remote (see and control the TV from your phone)

1. On the TV: **Shortcuts > Phone Remote > Turn on**. The screen shows an address and a PIN.
2. On your phone's web browser, open that address and enter the PIN. You get the live TV screen: tap it to click, drag to scroll, press and hold for a long press. There's also an on-screen remote (arrows, OK, Back, Home, play/pause) and a box for typing into search fields.
3. **From anywhere:** install the free **Tailscale** app on the TV (Amazon Appstore) and on your phone, and sign in to the same account on both. Then use the TV's Tailscale address (it starts with 100.). At home on the same Wi-Fi, no extra app is needed.

Phone Remote stays on, and comes back by itself after a restart, until you turn it off. Video from Netflix, Prime Video and other protected apps shows as black on the phone; everything else mirrors normally.
(Run Setup-Fire-TV.bat once with 2.6 or newer so the TV doesn't ask for screen-sharing permission each time.)

## Updates

Home Base checks for new versions every few hours. When one is out, a green **Update to x.x** button appears at the bottom of the screen. Press it and choose **Update**. It replaces the installed copy and keeps your teams, layout and Home button setup.
The first time, the TV asks you to allow Home Base to install updates: switch it **ON**, press **Back**, then press Update again.

## Undo everything

Double-click **[Undo-Fire-TV.bat](https://github.com/Scarpa86/fire-tv-home-base/releases/latest/download/Undo-Fire-TV.bat)** on the computer. It turns Amazon's apps back on, resets menu speed, turns the ad blocker off, unlinks the Home button, uninstalls Home Base and turns ADB debugging back off.
(No computer? On the TV, **Shortcuts > Setup & Undo > Undo everything** uninstalls Home Base, but it can't turn Amazon's apps back on.)
