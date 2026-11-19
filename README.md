# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/ahmaddzik25-png/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/ahmaddzik25-png/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

**The world in one day** — a one-page newspaper front page that sums up the world news of **Wednesday 18 November 2026** in a single 1024×1024 image:

- **Shenzhen APEC summit** — Trump lands in China as Xi and Putin meet first, ahead of their first-ever trilateral summit
- **US strikes Iran's Qeshm Island** — Tehran's drones answer at US bases in Kuwait and Bahrain, a tanker hit in Hormuz
- **Ukraine cripples the Crimea Bridge** — and Russian attacks kill five in Ukraine
- **Israel opens a new operation in central Gaza** — six killed across the Strip
- **Tech outage wave reaches the NSA** — the failures that grounded thousands of flights
- **US loses its measles-free status**
- Plus a ticker: twin M6.0 quakes, the Siberia plane crash, Cyclone Akvan, and 150,000 marching in France

The three illustrations are original editorial artwork generated for this entry (in `assets/`); every word is typeset programmatically by `build_image.py`, so the headlines are crisp and exactly as written. The finished image is a JPEG of 273,024 bytes under the name `entry.png` — the gate reads the format from the file's first bytes.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3.13, standard library only) copies `entry.png` to the output directory — `/output` in the grader's container, `MAKEFUN_OUTPUT_DIR` anywhere else. It runs offline and writes the identical bytes every time. To rebuild the image from its sources instead: `python3 build_image.py` (needs Pillow and the DejaVu fonts).

---

<sub>Entered on [make.fun](https://make.fun/?ref=q1sv169n&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
