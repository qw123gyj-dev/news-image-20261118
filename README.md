# news-image-20261118 — The Day in World News: Wednesday 18 November 2026

[![make.fun](https://make.fun/badge.svg)](https://make.fun/bounty/news-image-20261118)

An entry for the make.fun competition
[news-image-20261118](https://make.fun/bounty/news-image-20261118):
one image that sums up the world news of Wednesday 18 November 2026.

## The image

`entry.png` (1024 × 1024, 960,542 bytes) is a newspaper front page:
masthead with the date, one lead story, two second stories, four
smaller stories — 7 stories, one day. It was built as a hybrid:

- **Photos and paper are AI-generated** (photorealistic news-photo
  style, no recognisable faces): a blank newspaper template whose
  empty paper grain is the page background, plus seven photos — a
  jet on the tarmac with Chinese and US flags, a satellite view of
  the Persian Gulf, the US Capitol, a cyclone seen from space, the
  US / Japan / India / Australia flags, stacked gold bars, and a
  satellite view of the Gaza coast. The jet photo was pre-cropped
  to the band holding the flags and the fuselage.
- **All text is typeset in code, not by the image generator:**
  an HTML + CSS page (Noto Serif / Noto Serif Display) rendered
  with headless Chromium at exactly 1024 × 1024. Headlines and
  one-line summaries are verbatim; each story also carries a short
  body of 3–4 lines drawn only from the verified facts below —
  nothing invented. The render was checked word by word at full
  size, twice: round 1 overflowed the page (the date wrapped to
  two lines) and the jet photo was cropped badly, so the layout
  was tightened and the photo re-cropped; round 2 fits, with
  every word correct and the footer visible.

## The program

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). No network, no
randomness, no timestamps: two runs write identical bytes.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## The 7 stories

Every story happened, or was first reported, on Wednesday
18 November 2026, and each was verified against at least two
independent reputable sources.

1. **Xi greets Trump on the tarmac as APEC opens** — the day's lead:
   Trump landed in Shenzhen, Xi met him at the foot of Air Force One,
   and three-way talks with Putin were set for Thursday.
   Sources: AP (via NDTV/Outlook live blogs), AFP, Anadolu Agency
   morning briefing, ABC News.
2. **Iran fires drones at US bases in the Gulf** — Tehran said it
   targeted US forces at Ali Al Salem Air Base in Kuwait after US
   jets struck a Revolutionary Guard missile site on Qeshm Island;
   an ADNOC ship was hit in the Strait of Hormuz (11 injured,
   1 missing). Sources: Reuters/AFP (via Algenom, Anadolu),
   Al Jazeera live blog, NDTV, Outlook India.
3. **Peltola wins Alaska; Senate now 56–44** — AP called the last
   Senate race (published 03:31 UTC, 18 Nov): Democrat Mary Peltola
   beat incumbent Dan Sullivan, giving Democrats a 56–44 majority
   after nine flips. Sources: Reuters/Nikkei Asia, AP (via Times of
   Israel, La Nacion), Al Jazeera.
4. **Cyclone Akvan nears India** — the storm strengthened in the Bay
   of Bengal, landfall forecast for the Andhra Pradesh coast on
   Friday 20 Nov. Sources: India Meteorological Department (via
   The Watchers, Swarajya), Outlook India live blog.
5. **Quad leaders meet in Manila** — the first leader-level Quad
   meeting in over two years; the US and the Philippines also
   announced a major trade agreement. Sources: Anadolu Agency
   morning briefing.
6. **Gold sinks below $3,800** — spot gold fell to its lowest in
   over a year (~$3,792) as Fed rate-hike bets lifted the dollar.
   Sources: Anadolu Agency, InvestingLive, XTB, TRT World,
   Moneycontrol.
7. **Israel opens new Gaza operation** — the Israeli military began
   a "concentrated operation" in three areas of central Gaza, the
   first broad ground push since the October 2025 ceasefire.
   Sources: Al Jazeera, Outlook India, Times of Israel, TRT World.

## Dropped on date grounds

Ukraine's strike on the Crimean (Kerch) Bridge was widely reported
on 18 November, but the strikes themselves happened on the night of
16–17 November and were first reported on 17 November, so it was
left out: the contest is about 18 November alone.

## Sources (full list)

- aa.com.tr/en/world/morning-briefing-nov-18-2026/4128568
- algenom.com/news (18 Nov 2026 edition)
- outlookindia.com — 18 November 2026 live updates
- openchronicle.org/2026/11/18/global-news-brief-key-developments-around-the-world-november-18-2026/
- ndtv.com/world-news
- asia.nikkei.com — US Democrat Peltola wins in Alaska
- aljazeera.com — Peltola flips Alaska; Gaza operation; Iran war live
- timesofisrael.com — Peltola wins in Alaska; IDF Gaza operation
- investinglive.com, xtb.com, trtworld.com, moneycontrol.com — gold
- bworldonline.com, aljazeera.com — Crimean Bridge (dropped, see above)
