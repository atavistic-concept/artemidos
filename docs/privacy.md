# Privacy

[← back](../README.md)

No account. No analytics. No tracking. No advertising identifier. No third-party
SDKs, no crash reporting, no attribution frameworks.

## What can touch the network

Three things, and nothing else.

**Map tiles**, from `tile.openstreetmap.org`, only while the map is open and only
for ground not already stored. Whoever serves the tiles can see roughly *where
you are looking*, not where you are.

**Exchange rates**, from `api.frankfurter.dev`, once when the app opens online.
It sends nothing about you: no amounts, no currencies, no position.

**The licence server**, `admin.inritum.com`, and only if you buy or activate. It
receives an email address you typed, an order id, a licence key and a device
identifier. It never receives anything from the notebook, the radio keys, the
message log, or any position.

One switch in **Settings → Data** stops the first two entirely. Stored tiles
and the last rate table keep working.

## What never leaves

Position is read from the device and used on the device. The camera is used only
while the rangefinder is open, the microphone only while Morse or War Pigeon is
listening. Neither is stored or transmitted.

The notebook, the radio keys and the message log are held on the phone and sent
nowhere. That is the design, and also the warning: nothing is backed up, so a
lost phone loses them.

## The app lock

Optional. It encrypts the notebook, the radio keys, the message log and any
saved position with **AES-256-GCM**, under a key derived from your PIN with
PBKDF2-SHA256 at 210,000 iterations.

You can set two **duress PINs** alongside the real one:

- one opens an app that is only a calculator and a converter, with nothing else
  in it and nothing on screen saying so;
- one erases the notebook, the keys, the log and the stored map tiles, then opens
  that same empty app.

All three look identical from outside. The phone always holds three PIN slots
whether you configure one or three, so the number stored reveals nothing.

Four wrong attempts cost twenty seconds and minimise the app. The counter lives
on disk, so force-stopping and reopening does not reset it. Nothing is ever
deleted for guessing wrong.

**There is no recovery.** Forgetting the real PIN loses that data permanently.

### An honest limit

The cipher is sound. The weak point is that a PIN is short. Someone who takes the
phone, extracts the file and attacks it offline on a GPU is working through a
small keyspace: an eight-digit PIN is hours of work, not centuries.

It is good against someone who picks the phone up, someone who reads the storage
without cracking it, and the coercion case the duress PINs exist for. It is not
good against a well-resourced adversary who images the device and takes it away.
