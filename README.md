# 📡 PropDeck Companion

**The desktop companion for FT8 & FT4, by VE6KIX** — live roster with
GridTracker's colour language, DXCC & grid hunting against your own logbook,
POTA / SOTA / WWFF enrichment, QRZ.com & LoTW uploads, ADIF relays, and a live feed to
[PropDeck.net](https://propdeck.net).

## [⬇ Download the latest release](../../releases/latest)

One portable exe for Windows 10/11. No installer — `config.json` and `logs\`
are created beside it. The full manual (`MANUAL.md`) is attached to every
release.

**New in V1.20.0:** the roster’s **Dist** column now leads with an arrow for the short-path bearing to the station (`↗ 1.4k` = 1400 km to the north-east, in 45° steps), so you can see at a glance whether your antenna is pointed the right way; hover the row for the exact bearing in degrees. V1.19.0 made the roster row of whoever is calling you flash along with the **woop woop** and made the Log Map easier to read. All 20 language packs and offline manuals are current.

**Log Map.** Open the tab after **Call History** to explore your
master log on an offline dark or light world map. Track Maidenhead grids,
DXCC entities and CQ/ITU zones; filter contacts, preview or pin details, follow
live decoder stations and replay your log over time. **Pop Out** moves the
entire map workspace to another monitor, with its view and placement saved.

The interface, diagnostics and written manual are available in 20 offline
languages, matching PropDeck. Choose a language under **Settings → General →
Options**, then close and reopen Companion. **Open manual** opens help in your
selected language. Initial non-English translations are machine drafts and
may need fluent-speaker review.

**Last QSO** readouts and **Call History** show when you last worked a station
and let you browse every matching contact, including portable variants. Both
use your local master log and work offline, with larger text and roomier rows.

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
   and committed QSOs reach your local log and configured QRZ, LoTW, ADIF relay,
   and PropDeck.net destinations.

## Updating

The app checks this repository: **Settings → General → Options → Check for updates**.
It only checks when you click, and updating is just replacing the exe — your
config and logs live beside it and survive the swap.

---

> This repository carries **releases only** — the packaged application and
> its manual. Formerly published as *FT-Logger* (last release 1.3.3);
> versioning restarted at 1.0.0 under the PropDeck Companion name.
