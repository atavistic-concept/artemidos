# Installing on iPhone and iPad

[← back](../README.md)

There is no App Store listing and you do not need one. Artemidos installs
straight from the web, runs full screen, and works with no signal afterwards.

## The steps

1. Open **https://atavistic-concept.github.io/artemidos-pwa/** in **Safari**.
2. Tap the **Share** button, the square with an arrow coming out of the top.
3. Scroll down and tap **Add to Home Screen**.
4. Tap **Add**.

You now have an Artemidos icon on the home screen. Open it from there, not from
Safari, or you get a browser with an address bar instead of the app.

> **It must be Safari.** Chrome, Firefox and Edge on iPhone cannot create a real
> home-screen app, only a bookmark. This is an iOS restriction and nothing to do
> with Artemidos.

## Let it finish loading once

The first launch downloads the app so that later launches need no network. Give
it a minute on wifi before you rely on it. The reference photographs are fetched
only when you open the entries that use them, so browse the parts of Recon you
care about once while you still have signal.

## What works, and what does not

Everything computational works: the whole of Recon, the converter and
calculator, tides, sea navigation, mountain work, diving, radio and frequency
reference, Morse, War Pigeon, and all thirty languages.

The hardware picture is different from the Android app:

| | On iPhone |
|---|---|
| GPS | Works |
| Camera, for the rangefinder | Works. Grant the permission when asked |
| Microphone, for Morse and War Pigeon | Works. Grant the permission when asked |
| Compass | Works, using the heading iOS provides. Tap the compass once to allow motion access when prompted |
| **Vibration and haptics** | **Do not work.** iOS gives web apps no vibration at all |
| **Barometric altitude** | **Does not work.** It needs a sensor the browser cannot reach |

Everything else behaves as it does on Android.

## Keep the licence email

Deleting the web app clears its storage, and that takes the licence key, the
notebook and your saved settings with it. Nothing is lost permanently: the key
is in the email it came in and can be pasted back. See
[Buying and activation](activation.md).

iOS can also reclaim storage from apps you have not opened in a long time. It is
uncommon for a home-screen app, but it is the reason to keep that email rather
than treat the phone as the only copy.

## Updating

There is nothing to update by hand. The app checks for a new build when it has a
connection and replaces itself. Close it and reopen it to pick one up.

## If it will not install

- **No Add to Home Screen in the Share sheet.** You are not in Safari, or you
  are in a Private tab. Private tabs cannot install.
- **It opens with an address bar.** You launched it from Safari rather than from
  the icon.
- **A blank screen on first run.** The download did not finish. Reopen it with a
  connection and let it settle.

Still stuck: **atavisticconcept@gmail.com**
