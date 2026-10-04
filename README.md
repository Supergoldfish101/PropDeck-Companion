# 📡 PropDeck Companion

**The desktop companion for FT8 & FT4, by VE6KIX** — live roster with
GridTracker's colour language, DXCC & grid hunting against your own logbook,
FT8 Battle forwarding with UTC-day dupe blocking, POTA / SOTA / WWFF
enrichment, QRZ.com & LoTW uploads, and a live feed to
[PropDeck.net](https://propdeck.net).

## [⬇ Download the latest release](../../releases/latest)

One portable exe for Windows 10/11. No installer — `config.json` and `logs\`
are created beside it. The full manual (`MANUAL.md`) is attached to every
release.

**New in V1.9.0:** integrated **Last QSO** readouts show when you last worked
the current station. The **Call History** workspace searches a callsign and
lists every saved contact, including portable variants, newest first. Both
features use your local master log and work offline.

**Pairs with [PropDeck.net](https://propdeck.net)** — PropDeck in the
browser, Companion in the shack.

## Quick start

1. Put `PropDeck-Companion.exe` in a folder of its own and run it.

   > ⚠️ **First run:** Windows SmartScreen will warn about an unrecognised
   > app — click **More info → Run anyway**. Free, unsigned software; you
   > only do it once. (Or head it off: right-click the exe → **Properties**
   > → tick **Unblock** → OK.)

2. Point your decoder's *UDP Server / Reporting* at `127.0.0.1`, port `2237`
   (WSJT-X, JTDX, MSHV and Decodium 4 all work; multicast groups supported).
3. Operate. The roster fills, new DXCC light up, dupes get struck through,
   and every fresh QSO flows to FT8 Battle, QRZ, LoTW and PropDeck.net.

## Updating

The app checks this repository: **Settings → OPTIONS → Check for updates**.
It only checks when you click, and updating is just replacing the exe — your
config and logs live beside it and survive the swap.

---

> This repository carries **releases only** — the packaged application and
> its manual. Formerly published as *FT-Logger* (last release 1.3.3);
> versioning restarted at 1.0.0 under the PropDeck Companion name.
