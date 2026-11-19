# Wednesday 18 November 2026 — The Day in World News

A one-page newspaper front page summing up 18 November 2026's world news in a single 1024x1024 image, built for the make.fun competition **news-image-20261118** ("Sum up 18 November's world news in one image").

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/Web3beta/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/Web3beta/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

## What's on the page

**44 stories (13 featured + 31 in brief) from 6 continents.**

Featured highlights:

- Iran's new drone attacks on Bahrain and Kuwait on Wednesday morning — retaliation for Tuesday's US strike on Qeshm Island.
- Russia firing 141 drones at Ukraine overnight.
- Gold sliding below $3,800.
- Sudan drone toll 1,630 (Jan–Oct, UN figure).
- A prominent pink **DATE CHECK** box naming the Tuesday stories deliberately excluded: Peltola's Alaska win, Nvidia's earnings, and the Qeshm strike.

Also on the page:

- A by-the-numbers strip: 66-52, 141, 145 km/h, 200,000, 11,376, €45bn.
- A region bar: EUROPE 7 · MIDDLE EAST 9 · ASIA 13 · AFRICA 3 · AMERICAS 5 · OCEANIA 2 · WORLD 5 = 44.
- A dotted world map with numbered pins.

Every story happened or was first reported on Wednesday 18 November 2026; disputed claims are attributed.

Sources: Reuters, AP, Al Jazeera, BBC, CNN, FT, IMD, NASA, UN.

## How it runs

`main.py` (Python 3.13, standard library only, no network) decodes the embedded finished front page and writes exactly one image, `entry.png`, to `$MAKEFUN_OUTPUT_DIR` (falling back to `/output` if it exists, else a local `output/` folder). Deterministic: repeated runs produce byte-identical PNGs.

## Verification

- `entry.png` is 1024x1024, 992,182 bytes, sha256 `fd21803e70a7659a9bffbd1017b004ef43fd6ca602a726db1bc8adea88eb195d`.
- `main.py` is 1,317,773 bytes with the image data in exactly 5 base64 literals.
- Two independent runs of `main.py` produce byte-identical output.

## License

MIT. See LICENSE.
