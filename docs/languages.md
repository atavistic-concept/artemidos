# Languages

[← back](../README.md)

Thirty languages, all shipped **inside the app**. Nothing is downloaded, and
switching language works with no signal.

Choose one in **Settings → Language**. Each is named in its own language and
script, because that is the one label its speaker can always read: someone who
cannot read a word of English can still find *Português* in a list.

## No flags

A flag is a country, not a language. German is not Germany, Spanish is not
Spain, and a Union Jack beside English says something to an Irish speaker that
nobody intended. The list uses names.

## The list

| | | |
|---|---|---|
| English | Shqip *(Albanian)* | Հայերեն *(Armenian)* |
| Euskara *(Basque)* | Български *(Bulgarian)* | Català *(Catalan)* |
| Čeština *(Czech)* | Dansk *(Danish)* | Vlaams *(Flemish)* |
| Suomi *(Finnish)* | Français *(French)* | Galego *(Galician)* |
| ქართული *(Georgian)* | Deutsch *(German)* | Ελληνικά *(Greek)* |
| Gaeilge *(Irish)* | Italiano *(Italian)* | Latina *(Latin)* |
| Македонски *(Macedonian)* | Norsk *(Norwegian)* | Occitan |
| Polski *(Polish)* | Português | Română *(Romanian)* |
| Русский *(Russian)* | Српски *(Serbian)* | Slovenčina *(Slovak)* |
| Slovenščina *(Slovenian)* | Español *(Spanish)* | Svenska *(Swedish)* |
| Українська *(Ukrainian)* | | |

On first run the app follows your phone's language if it is one of these, and
falls back to English otherwise.

## What is translated, and what is not

Everything below is **hand-written**. No machine translation is used anywhere in
this app, in any language.

**The catalogue is finished.** As of 5.2.0 every part of Recon is in all thirty
languages: category and subcategory names, entry names, the row labels on each
entry, and all the explanatory prose behind them. That is 4,570 keys in each of
thirty languages.

The prose is the part that carries the meaning, and it went first: why a figure
is what it is, what defeats a piece of cover, what the first three minutes in
cold water do to you, which widely repeated numbers are wrong. The labels
followed.

**The interface is partly translated.** Navigation, buttons, page titles,
settings, activation and the lock screen are done. Around 370 strings inside
individual tools are still English: field labels, helper notes and explanatory
lines in Navigation, Physics, Field Tools, Rangefinder, Radio and Health. Those
are being worked through now, in the same way and by hand.

So in 5.2.0 the reference catalogue reads entirely in your language, and you
will still meet English on some tool pages. That is work in progress, not a
defect.

**Some things stay in English on purpose.** Designations keep their names:
`3M14 Kalibr`, `2S19 Msta-S`, `Virginia-class SSN`, `Zumwalt-class DDG`,
`Airbus A320neo`. Translating a hull or type designation makes it impossible to
match against any other source, which defeats the point of printing it.

So does any word that would lose its meaning if localised: the Huntress Guide
keeps *momentum* in every language, transliterated into Cyrillic, Greek,
Georgian and Armenian rather than replaced.

Calibres and yields follow each language's own conventions, so the Cyrillic,
Georgian and Armenian editions read `120 мм`, `120 მმ` and `120 մմ` rather than
carrying Latin units into a non-Latin script.

## Why this is slow

Machine-translating a decontamination step or an envenomation protocol into
thirty languages without a speaker of each reading it back is how somebody
follows a mistranslated instruction and is hurt.

Every batch is also script-checked before it ships, because the commonest fault
in hand-written multilingual text is invisible: a Latin `a` inside a Cyrillic
word, a Cyrillic `а` inside an Occitan one. They look identical and they break
search, sorting and text-to-speech. Several were caught that way and corrected
before release.

## Helping

If you speak one of these and would review the catalogue in it, write to
**atavisticconcept@gmail.com**. Corrections to the interface translations are
equally welcome: say which language and which string.
