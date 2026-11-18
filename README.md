# Wednesday 18 November 2026 — The Day in World News

A one-page newspaper front page summing up 18 November 2026's world news in
a single image, built for the make.fun competition
`news-image-20261118` ("Sum up 18 November's world news in one image").

## Badges
[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/Web3beta/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/Web3beta/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

## What it is

- 40 stories from 6 continents on one 1024x1024 page.
- 9 featured stories: 3 with original illustrated panels (US-Iran strikes
  over Bahrain and Qeshm, the Crimea bridge span falling, Trump in Manila
  then Shenzhen) and 6 with icons (Nvidia's $115.8bn quarter, the Knesset
  electing Kahana, the EU's €45bn Ukraine loan, Cyclone Akvan, Wall Street's
  slide, APEC opening in Shenzhen).
- A by-the-numbers strip (66-52, $115.8bn, 145 km/h, 200,000).
- A dotted world map with numbered dots for stories 1-9.
- 31 more stories in brief, including Peltola's Alaska win, the Ebola surge,
  Cyclone Xavier, the World Court's Myanmar ruling, the Papua New Guinea
  quake, and Trump open to meeting Kim Jong Un.

Every story on the page happened, or was first reported, on Wednesday
18 November 2026. Disputed claims are attributed. Sources: Reuters, AP,
Al Jazeera, BBC, CNN, FT, IMD, NASA, UN, UEFA, ESPNcricinfo.

## How it runs

`main.py` (Python 3.13, standard library only, no network) decodes the
embedded finished front page and writes exactly one image, `entry.png`, to
`$MAKEFUN_OUTPUT_DIR` (falling back to `/output` if it exists, else a local
`output/` folder). The output is deterministic: both grader runs produce
byte-identical PNGs.

## License

MIT. See [LICENSE](LICENSE).
