# FulgurStack releases

Alpha builds of **FulgurStack**, a stacking and calibration application for astrophotography (FITS and XISF lights from smart telescopes and astro cameras), for Windows 10 and 11 (x64). This repository holds the downloads only; the source code is not published here.

## Download

Go to **[Releases](../../releases)** and download the ZIP of the latest version, for example `FulgurStack-0.14.0-<commit>-windows-x64.zip`.

There is no installer. Unpack the ZIP anywhere and run `fulgurstack-gui.exe`. The package also holds `fulgurstack.exe` (command line), `fulgur-solve.exe` (blind plate solver), a short guide `CTI_ME.txt` (Czech) and the alpha testers' guide (PDF, Czech).

## Good to know

- The programs are **not code-signed**, so Windows SmartScreen may warn on the first start: choose *More info*, then *Run anyway*.
- Check the download against the SHA-256 listed in the release notes.
- Input files are only read, never changed. Settings are kept in `%LOCALAPPDATA%\FulgurStack`.
- Plate solving and blind solving need the PixInsight Gaia DR3 files (`gdr3-*.xpsd`, about 44 GB).
- Tested on Windows 11 x64 only; this is an alpha version, provided as is for testing.

## Feedback

Send problems with a description of the steps, a screenshot and the `*_report.json` file of the run.

---

## Cesky

Alfa verze aplikace **FulgurStack** pro skladani a kalibraci astrofotografii (FITS a XISF z chytrych teleskopu a astro kamer), pro Windows 10 a 11 (x64). Zde jsou jen stazitelne balicky, zdrojovy kod zde neni.

**Stazeni:** v sekci [Releases](../../releases) stahnete ZIP nejnovejsi verze. Instalace neni potreba: rozbalte a spustte `fulgurstack-gui.exe`. Program neni digitalne podepsany, Windows SmartScreen proto muze pri prvnim spusteni varovat (*Dalsi informace*, pak *Presto spustit*). Kontrolni soucty (SHA-256) jsou v popisu kazde verze. Podrobnosti jsou v `CTI_ME.txt` v balicku.
