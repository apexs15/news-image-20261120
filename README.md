[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/apexs15/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/apexs15/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

# THE WORLD — Friday, 20 November 2026

A newspaper front page summing up the world's news of Friday, 20 November 2026, drawn as one image for the make.fun bounty [Sum up 20 November's world news in one image](https://make.fun/bounty/news-image-20261120).

## What the front page shows

The lead story is the International Court of Justice ruling 9–6 that Myanmar committed genocide against the Rohingya — the first such finding against a state by the world court — with a drawn scales-of-justice illustration. Below it, the first three-way summit of Trump, Xi and Putin in Shenzhen, and Anthropic's Nasdaq debut, up about 17% on its $83 IPO price. A third row covers the Houthi missile that damaged Riyadh's tallest tower and the overnight attack on Kyiv as Ukraine struck the Crimea Bridge a third time that week. An "In Brief" strip closes the page: five straight days of US stock falls and the Nikkei's 4.8% drop, the Berlin allies' meeting, GTA 6 passing $2.3 billion in sales, Kenya's last Ebola patient discharged, an FAA ground stop stranding 1.5 million travellers, the IMF's debt warning, and Italy's €805 million fine on Meta.

The page was rendered locally from HTML and inline SVG — no photographs, no external assets — in the style of a classic broadsheet: a big "THE WORLD" masthead, the date in red, and short headlines a reader can take in at a glance.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to the output directory as `entry.png`. Running it twice writes byte-identical files.
