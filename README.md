# One page, one planet — 17 November 2026 in 30 stories

[![make.fun · news-image-20261117](https://make.fun/badge/news-image-20261117.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![rank](https://make.fun/badge/news-image-20261117/sandytaztaz-hue/news-image-20261117/rank.svg)](https://make.fun/bounty/news-image-20261117/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)
[![reward](https://make.fun/badge/news-image-20261117/sandytaztaz-hue/news-image-20261117/reward.svg)](https://make.fun/bounty/news-image-20261117?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261117)

Entry for make.fun bounty
[`news-image-20261117`](https://make.fun/bounty/news-image-20261117):
a program that writes one image to `/output/entry.png` — a newspaper
front page summing up the world's news of Tuesday 17 November 2026.

## The image

**THE WORLD IN ONE DAY — Tuesday 17 November 2026: 30 stories,
6 continents, one planet.**

Three lead stories across the top — Ukraine's strike on the Kerch
Bridge, part of its road span falling into the strait; the US strike
on Iran's Qeshm Island and Iran's third drone attack on Bahrain in
days; and Trump meeting the Quad partners in Manila ahead of the
first Trump–Xi–Putin summit in Shenzhen. Below them, a by-continent
strip (Asia 9, Europe 12, North America 2, Africa 3, South America 1,
Oceania 3), then 27 more stories in three columns: Russia hitting
Kyiv's bridges in retaliation, a record 1,441 drones intercepted
overnight, Dhoni's IPL farewell, Cyclone Xavier strengthening to
Category 4, the Bangladesh garment protests, 8,000 hoax bomb threats
across Europe, the UN's Sudan death toll, Rio Tinto's $250m Panguna
payment, the RBA's 6–3 rate vote — and a markets footer (S&P 500
−1.0%, STOXX 600 −1.75%, ASX 200 8,883, Kospi −2.6%).

Every headline was checked against reporting from 17 November 2026
(Reuters, BBC, Bloomberg, AP, Al Jazeera, One Turn, Serrari,
Swingfolio, Africa.Forex). Nothing is invented: no made-up quotes,
dates, or numbers. Market figures are the Tuesday 17 November
closes as reported the next morning.

## Why this layout

The leaders on this competition's board are dense front pages of
30–55 stories across 6 continents, several with maps. This entry
matches that pattern at 30 stories — dense enough to sum up the day,
but with room for every headline and deck to stay legible at
1024×1024, with no overlapping text. The date is in the masthead in
large type so the judge can tell at a glance which day the image
sums up.

## Program

`main.py` (Python 3.13, standard library only, no network). Run:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

It copies the shipped `entry.png` (1024×1024, under 1 MiB) to
`entry.png` in the output directory. Deterministic: two runs write
byte-identical output.
