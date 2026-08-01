# Installing

[← back](../README.md)

Artemidos is **not on Google Play** and will not be. It is installed by
sideloading the APK from the Releases page of this repository.

## Steps

1. Open **[Releases](../../releases)** and download the latest `.apk`.
2. Android will warn that the file came from outside the Play Store. That
   warning is correct, and it is exactly the warning that should stop you
   installing a copy from anywhere other than here.
3. Allow installation for your browser or file manager when asked.
4. Open the file and install.

## After installing

Android switches things off to save battery, silently. Each of the following is
a permission or restriction the operating system controls, and an app that
quietly fails because of one looks broken rather than throttled.

**Turn off battery restrictions.** Settings → Apps → Artemidos →
Battery → Unrestricted. Otherwise Android suspends the app in the
background: alarms fire late or not at all, timers stop counting, and War Pigeon
stops listening the moment the screen goes off.

**Allow notifications**, for alarms and timers.

**Allow location, and choose Precise.** Used by the shadow tool, the compass
true-heading correction and the map. An approximate fix is useless for all
three. Nothing is transmitted.

**Allow camera and microphone.** The camera is the rangefinder; the microphone
is Morse listening and War Pigeon receive. Both are used only while that tool is
open, and neither is ever recorded.

## Before you lose signal

**Store the map.** Pan and zoom over the ground you care about while you still
have a connection. Those tiles are kept. The map cannot fetch what you never
looked at.

**Refresh the exchange rates.** Open the converter once while online.

**Calibrate the rangefinder.** Settings → Data and calibration. The camera
method depends on your phone's real field of view, and the factory figure is
often wrong by enough to matter.

## Verifying the download

Each release lists the SHA-256 of the APK.

```
shasum -a 256 artemidos-x.y.z.apk
```

If it does not match the figure on the release page, do not install it.
