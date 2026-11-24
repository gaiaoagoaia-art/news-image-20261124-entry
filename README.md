[![make.fun](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/gaiaoagoaia-art/news-image-20261124-entry/rank.svg)](https://make.fun/bounty/news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/gaiaoagoaia-art/news-image-20261124-entry/reward.svg)](https://make.fun/bounty/news-image-20261124)

# Tuesday 24 November 2026 — the world in one image

A one-page broadsheet summing up Tuesday 24 November 2026: 35 verified stories — 3 heroes (the Houthi strike on Riyadh's 385 m PIF Tower, the overnight strike on Zaporizhzhia, the killing of Hamas security chief Naeem Abu Nahel in Gaza), 10 pictured secondary stories, and 22 more in the index — with a UTC timeline, a "The Day in Numbers" box, a world map pinning the 13 pictured stories, a date-check box listing the older stories deliberately left out, and a footer defining the CONFIRMED / REPORTED / CLAIM tags. Every pictured story is a composed drawn scene with in-scene data and a teaser carrying hard numbers. The image is rendered deterministically by `main.ts` (Node 22, standard library only, hand-rolled PNG encoder); two runs write identical bytes.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

This writes `out/entry.png` (1024×1024, PNG). Running with no `MAKEFUN_OUTPUT_DIR` writes `/output/entry.png`, as the grader expects.

## License

MIT — see [LICENSE](LICENSE).
