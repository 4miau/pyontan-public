# Troubleshooting

The usual problems and what fixes them. Still stuck? [Send feedback](https://pyontan.com/feedback), [open an issue](../../../issues) or ask in [Discord](https://discord.gg/Pz3gCFPejV).

## Installing and starting

- **"Windows protected your PC"**: press More info, then Run anyway. The app isn't code-signed yet
- **Smart App Control blocks it** (Windows 11): message me and I'll help
- **Nothing happened**: pyontan is in the tray by the clock, maybe under the ^ arrow
- **Signed in as the wrong account**: the app signs in as whoever is signed in on the website in your browser. Log out there, then sign in again

## Translation

- **"... isn't set up yet"**: the translation service you picked is missing a key or a model (Settings > Providers)
- **"... rejected this API key"**: a wrong key, or one copied with a space
- **"Couldn't reach ..."**: no internet, the service is down, or a local model server isn't running
- **Out of lines for today**: wait for tomorrow, use Mochi or your own key, or upgrade. Settings > Billing > Usage on the website shows what's used

## OCR Capture

- **"(nothing found)"**: add Japanese as a language in Windows' settings, drag a bigger box, or try the Paddle or Manga engine

## Live Audio

- **Won't start**: install its add-on (Settings > Live Audio > Add-ons)
- **Nothing appears**: the wrong audio source, or nothing playing on it
- **Falling behind**: pick a smaller model, or Streaming mode

## Song Lyrics

- **Nothing shows**: the player has to show in Windows' media controls
- **"No timed lyrics found"**: that song's lyrics aren't published with timings

## Study

- **Reviews due on one device but not another**: give it a minute to sync, then check the time zone (Settings > Study)

## Android and Screen translate

- **"Restricted setting" when allowing the bubble**: Settings > Apps > pyontan, tap ⋮, then Allow restricted settings
- **Black picture**: that app blocks screenshots
- **"Couldn't reach pyontan"**: check your connection

## Browser extension

- **Nothing translating**: check the popup is signed in, or, with the app, that the app is running and the popup says Connected
- **Firefox for Android**: there's no right-click there. Long-press Japanese and tap 訳

## Telling me about it

Say what you did, what happened, and the version (in the Windows app, the top of the tray menu's Help).
