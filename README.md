# 23 November 2026 in one image

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/sontv01034/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/sontv01034/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

One image summing up the world's news of Monday, 23 November 2026, built for the make.fun bounty of the same name.

## The day, in six stories

- **COP31 collapses** — The Antalya climate summit ends with no agreement; the draft stays silent on fossil fuels.
- **Huang returns** — Nvidia's board reinstates co-founder Jensen Huang as chief executive, days after he stepped down.
- **Missiles over the Gulf** — Iran launches its heaviest missile week in over a year; Trump says all were shot down, while mines hit three tankers in Hormuz.
- **Strikes on Ukraine** — A Russian missile hits Kryvyi Rih, killing two including a 7-year-old; a drone brings down an apartment block in Dymer.
- **Factory fire** — 24 killed in a factory blaze in Indonesia as rescuers search for dozens missing.
- **Democrats 258** — Democrats take 258 House seats, their largest majority since 1992.

Also: Bitcoin slides to $55,100, its lowest since September 2024; India gives Nepal a $1.62bn flood-aid package; an Israeli strike on a Gaza truck kills three.

## How the image is made

`entry.png` (1024×1024) is drawn programmatically with Python and Pillow — a light broadsheet front page with one tile per story, so every word stays legible even at small sizes. No AI image generation was used for the text.

`main.ts` is the entrypoint: it copies `entry.png` to the output directory the grader provides.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Sources

Reuters, AP and AFP reporting from 23 November 2026.
