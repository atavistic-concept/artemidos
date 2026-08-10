# Installing in a browser, Android and desktop

[← back](../README.md)

The web version is the same Artemidos as the Android APK, served from a page
instead of a file. It installs to the home screen or the desktop, runs in its
own window, and works afterwards with no signal.

**https://atavistic-concept.github.io/artemidos-pwa/**

On Android the APK is still the better build, because it reaches sensors a
browser cannot. Use the web version when you would rather not sideload, or when
you are on a machine that cannot run an APK at all.

## Android, Chrome or Edge

1. Open the address above.
2. Take **Install app** from the banner, or open the **⋮** menu and choose
   **Install app** or **Add to Home screen**.
3. Confirm.

Firefox on Android puts the same thing under **⋮ → Install**.

## Windows, macOS and Linux

In Chrome or Edge, open the address and click the **install icon** at the right
of the address bar, then **Install**. It gets its own window and a normal
launcher entry.

Safari on macOS: **File → Add to Dock**.

Firefox on the desktop does not install web apps. Artemidos still runs perfectly
in a normal Firefox tab, it simply will not get its own window.

## Let it finish loading once

The first visit downloads the app so later launches need no network. Give it a
minute before relying on it offline. Reference photographs are fetched only when
you open the entries that use them, so browse what you care about once while you
have a connection.

## What works, and what does not

Everything computational works, in every browser: Recon in full, the converter
and calculator, tides, sea navigation, mountain work, diving, radio and
frequency reference, Morse, War Pigeon, and all thirty languages.

| | In a browser |
|---|---|
| GPS | Works, though a desktop derives position from the network and is far less accurate than a phone |
| Camera and microphone | Work. Grant the permission when asked |
| Compass | Works on phones. Desktops have no magnetometer, so it stays blank |
| Vibration | Works on Android. Never on iOS, and desktops have nothing to vibrate |
| Barometric altitude | Needs a sensor no browser can reach. Android APK only |

The **camera rangefinder** deserves a warning on desktop. It works out distance
from the camera's field of view, and a laptop webcam is not the camera it was
calibrated against, so treat any figure it gives you there as meaningless.

## Keep the licence email

Clearing site data, or removing the installed app, clears the licence key, the
notebook and your settings. The key itself is not cancelled and can be pasted
back from the email it came in. See [Buying and activation](activation.md).

## Updating

Nothing to do. The app fetches a new build when it has a connection and swaps
itself over. Close it and reopen to pick one up.

## Questions

**atavisticconcept@gmail.com**
