# What Artemidos does

[← back](../README.md)

The app has four sections along the bottom: **Console**, **Recon**,
**Navigation** and **Field**. Everything below lives in one of them.

---

## Console

The home screen, arranged by whoever carries it.

Everything else in the app is organised the way the *subject* is organised , 
ballistics with ballistics, radio with radio. That is right for reference and
wrong for a job, because a job draws two tools from one section and one from
another. The Console is the answer.

**Shortcuts.** Pin any page in the app. Reorder them, remove them, add more.
Every registered page is available, including tools that live inside another
page such as Morse or War Pigeon.

**Clocks.** Named clocks across time zones, three to a row. Working across zones
is where mistakes are made that look like incompetence, a call missed by an
hour, a curfew misjudged, and a row of clocks settles it. Daylight saving is
handled from the device's own time zone database.

**Huntress Guide**, **About Artemidos**, **Settings** and **Other apps**.

---

## Recon

The reference catalogue. Around a thousand entries, each storing its figures in
SI and displaying them in whatever units you chose.

| Section | What is in it |
|---|---|
| **Physics & nature** | Wave speeds, falling bodies, ballistic arcs, natural phenomena, and a **cloud field guide**: the ten types, what each looks like, and what it says about the next few hours |
| **Civilian vehicles** | Road, rail, air and sea, with range and endurance |
| **Military systems** | Tanks, armoured vehicles, artillery, aircraft, helicopters, naval vessels, drones, missiles, ICBMs, nuclear effects, air defence, plus **ranks and insignia**, **camouflage patterns** and **police forces** by country |
| **People & animals** | Movement rates, endurance and daily range |
| **Ballistics & cover** | Threat ranges, what stops what, protection standards |
| **Radiation & shielding** | Radiation types, what blocks them, how thick, by isotope |
| **Infrared & thermal** | What thermal and IR see, how far, and what defeats them |
| **UXO & explosive hazards** | Recognition, why it is still live, how far to go back |
| **Chemical agents** | Recognition, protection, decontamination, treatment |
| **Biological & decay** | How long since: bodies, food, mould, dust, abandonment |
| **Countries** | Currency, emergency numbers, police and intelligence services, plugs, cities |

### Animals

Every species answers three questions before it answers speed:

- **If you meet one**, what to actually do, in plain terms
- **How far it detects you**, hearing, sight, smell, and pressure sense where it has one
- **Where it is found**

Sprint distance before an animal breaks off is given where it matters: a tiger
gives up after about 200 m, a cheetah after 500, an African wild dog holds
48 km/h for five kilometres.

Two entries invert the usual ranking, and say so: the **mosquito** kills more
people annually than every other animal combined, and the **domestic dog** is
second, almost entirely through rabies.

### Tools inside Recon

**Range graphics** on any item with distance figures: danger rings drawn to
scale from the entry's own numbers.

**Firing solution** on individual weapons: elevation and windage for a given
range, wind, temperature and height difference, computed with a point-mass
model and a G1 drag curve rather than looked up in a table.

**Timeline calculator** in Biological: rescales any published decay window for
real temperature, humidity, and whether the subject is in air, fresh water, salt
water or buried.

---

## Navigation

### Maps

**Range map.** A real, pannable world map. Drop weapon, blast, nuclear or sound
ranges onto any location as true geographic circles and read which real places
fall inside a ring. Tiles you have panned over are stored and work with no
signal afterwards.

### Instruments

**Compass.** Full dial, magnetic and true heading. **Calibratable**: point the
phone at a bearing you know, enter it, and the offset is stored and applied
everywhere afterwards, including the floating mini compass. A phone
magnetometer is a chip inside a slab of metal and magnets, and it reads
consistently wrong by an amount that depends on the phone, the case and what is
in your pocket.

**Fuel.** Fuel and range for land, sea and air, in three tabs. Every figure
starts from the consumption *you* enter and bends it with the conditions the
maker's number quietly assumed away.

- *Land*, a sustained uphill gradient costs real litres, computed from the mass being lifted, the fuel's energy and drivetrain efficiency, and added to the flat-road figure
- *Sea*, a stated weather allowance from significant wave height, wind and the heading they come from: worst into a head sea, nearly free following. The breakdown is shown, so the estimate is never hidden inside the answer
- *Air*, the burn is by the hour but the ground covered is not, so the wind component drives groundspeed, trip fuel, reserve in minutes and the total required

### In the hills

**Mountain.**

- **Time**, Naismith, plus load, party size and a penalty for steep descent, with the moving time, the figure to give someone expecting you back, and what it looks like if it goes badly
- **Slope distance**, a map measures the ground flattened; on a 30° slope a map kilometre is 1,155 m under your boots
- **Height**, from a clinometer angle and a paced horizontal distance, with what one degree of error is worth at that range
- **Gradient**, rise over run, as a percentage, an angle and a ratio, with the **avalanche band** called out: 30° to 45° is where slab avalanches overwhelmingly release

### On and in the water

**Tides.** Offline tide prediction for ports worldwide, with the curve drawn at
the top of the page. Stations with published harmonic constants are computed
from them; elsewhere the app works from the moon's transit with a standard-port
high-water interval and range, and says plainly which of the two it used and
where the figures were borrowed from.

**Scuba.**

- *Gas*, mixes, best mix for a depth, maximum operating depth, equivalent narcotic depth, oxygen partial pressure
- *Pressure*, absolute and gauge pressure against depth, in fresh or salt water and at altitude
- *Dive plan*, no-stop time and decompression on **Bühlmann ZH-L16 with gradient factors**, sixteen tissue compartments shown as they load, multi-level segments and gas switches, with conservatism presets
- *Gas plan and consumption*, surface air consumption from a real measurement, the rule of thirds, and how long a cylinder lasts at a depth
- *Weighting*, lead for suit, salinity and cylinder, including twinsets and sidemount
- *Fill*, cylinder filling time from start and end pressure and the compressor's rate

**Free-diving.** Lead weighting from body mass, suit thickness and salinity, set
for neutral buoyancy where it matters rather than at the surface.

**Sea navigation**, sailings (great circle and rhumb line), chart scale, true/magnetic/compass conversion, course to steer with tidal set and drift, tacking, estimated position, speed–time–distance.

**Magnetic declination**, today's figure from an offline world magnetic model, *and* what an old chart's own compass rose works out to now. A 1994 chart with 6′ annual change is three degrees out by now, and three degrees over ten miles is half a mile off track. It shows both and states the disagreement.

**Distance off**, vertical sextant angle, dipping lights, two bearings.

### How far

**Rangefinder**, distance by camera (after calibration), by mil scale against a
known height, and by flash to bang.

On the camera there are two crosses: a fixed one at the exact centre and a red
one you slide sideways. The app reads the angle between them off the lens
geometry and gives the **separation between the two objects** in degrees,
milliradians, NATO mils and, once a range is known, in metres. The readout sits
bottom right, outlined so it stays readable against a bright sky or a dark
treeline.

**Between places**, road, helicopter and jet times between any two places.
Typing a city offers its centre *and* every airport within 75 km, each with how
far out it sits and tagged **military** or **private** where it is not a
scheduled airport. Coordinates are shown for both ends.

---

## Field

**Calculator**, scientific, with a running **tape**: finished sums stack above
the live one, newest at the bottom, and tapping any line drops its result into
the current expression.

**Converter**, every measure, fully offline.

**Notebook**, categorised notes, encrypted when the app lock is on.

**Time**, stopwatch, timers and alarms.

- *Round*, an interval timer that beeps, vibrates or both at every interval you set, in seconds, minutes or hours, with a choice of the double tone or a single one
- *Marks*, a countdown can also sound at up to three exact times on its way down, each set to a single or double beep
- *Presets*, name a timer or a round set and load it again later

**Radio**

- *Range*, estimation over real terrain, for PMR446, FRS, GMRS, MURS, CB, marine VHF, airband, amateur bands, TETRA, LoRa and custom frequencies
- *Radios*, sets and their specifications, followed by **emergency frequencies**: distress and calling channels by country, region and international convention, maritime and mountain rescue, and the weather broadcasts that apply where each is used
- *Morse*, a straight key first, then write, listen, and a practice tree that lights under your thumb as you key. The writing page carries collapsible reference boards: the code chart itself, operating **abbreviations**, the **Q code** with its aeronautical additions, and the **Z code**
- *War Pigeon*, see below
- *Planner*, channel cards and frequency planning

**Phonetic**, NATO/ICAO, and the **Russian alphabet in Cyrillic**: all 32
letters plus digits, each showing the code word and how to say it. Type Latin
and it transliterates, showing both letters so you can see which Cyrillic one is
meant.

**Currency**, offline, from the last European Central Bank table stored.

**Health**

- *Pulse*, tap once per beat and it counts the rate, says whether it sits high, low or normal for a resting adult, and explains what that reading does and does not mean. A finger and a clock cannot support a diagnosis, and the page says so rather than pretending otherwise
- *CPR*, a metronome at 100 to 120 a minute with the 30:2 cycle counted for you, 5 to 6 cm depth called out, five cycles to the two-minute swap, and the two variations that matter: compressions only if you are untrained, continuous compressions with one breath every six seconds once an airway is in
- *Body*, the human reference figures: normal and abnormal body temperature, the hypothermia bands, fever, heat illness and insolation, resting pulse by age, and how long dehydration takes to matter
- *Period*, a calendar you log period start and end days into. It predicts the following cycles, ovulation, and the follicular and luteal phases, and it recalculates from your own logged dates rather than an assumed 28 days. Anything it predicts can be overwritten with what actually happened, and the next prediction takes that in

**Sensors.** What this particular phone actually has. The page probes for
battery state, charge, voltage and temperature, GNSS, compass and magnetometer,
ambient light, barometer, thermometer, hygrometer, clinometer and microphone,
and reports each as present with its reading, or plainly **not available**.

Where a sensor exists but Android does not expose it to an app, the page says
that instead, because "not available" and "present but not offered to this app"
are different facts and only one of them is about the hardware.

---

## War Pigeon

An **OFDM data modem** that carries short encrypted text over any voice channel:
speaker to microphone, radio to radio, phone to phone. No infrastructure, no
network, no pairing.

It sends a real signal, not beeps: 32 or 8 carriers with differential BPSK, a
matched-filter chirp for synchronisation, Hamming(7,4) with interleaving,
CRC-16/CCITT integrity, and soft-decision decoding with soft-combining across
repeats.

Two modes: **fast** for a clean channel and **robust** for a poor one. Messages
are encrypted with a key you set; keys are shared out of band. It stops
listening while transmitting so it never decodes itself.

---

## Themes and legibility

Six themes in three families, each with a light and dark version:

**Artemis**, the everyday one.
**Raider**, monochrome and near black, condensed capitals, corner brackets on
whatever is selected, flat frosted glass panels.
**Military**, HUD is phosphor green with seven-segment figures; RED is a
deep-red low-light scheme that reads after dark without destroying dark
adaptation and dims the camera preview to match.

**Text size** is adjustable from 80% to 120%. It changes the *text* only:
buttons, icons and spacing stay where they are, so nothing moves and nothing is
pushed off the edge.

---

## App lock

Optional, and covered in full under [Privacy](privacy.md): AES-256-GCM over the
notebook, radio keys, message log and saved positions, with an unlock PIN and
two optional **duress PINs**, one that opens a harmless calculator-only app,
one that erases everything first.

---

## What needs a connection

Almost nothing. Map tiles for ground you have not already stored, exchange rates
once a day, and the licence server if you buy or activate. Everything else, including
the entire catalogue, every calculation, navigation, ballistics, radio planning,
Morse, War Pigeon, the notebook, runs with the phone in flight mode.

Listed in full under [Privacy](privacy.md), and inside the app under
**Settings → What uses the network**.
