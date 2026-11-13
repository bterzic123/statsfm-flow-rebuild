# Growth Audit — stats.fm

**Live:** https://bterzic123.github.io/statsfm-flow-rebuild/
**Prototype:** https://bterzic123.github.io/statsfm-flow-rebuild/?view=proto

stats.fm's quiz finds every new user's #1 artist before the paywall, and then the paywall says "Unlock everything". This audit rebuilds the first launch in stats.fm's own design and prices, so that Pro answers with the user's own artist. It has three phones, one each for the ranking ad on Meta, the 400-hours ad on Meta and an Apple Ads search for "spotistats".

## The five ideas

| # | Idea | Screen | Expected impact |
| :-- | :-- | :-- | :-- |
| 1 | Name their #1 artist in the Pro headline | Pro | CR +15–20% |
| 2 | Show the locked number on the payoff | Payoff | CR +10–20% |
| 3 | Ask for notifications after Pro, not on the first slide | Home | CR +10–15% |
| 4 | Put your rating next to the price | Pro | CR +10–15% |
| 5 | Bring the plans up and make Pro the obvious pick | Pro | CR +5–15% · ARPU +3–8% |

Impact ranges are Adapty's expected effect from teardowns and A/B tests across subscription apps. They are not measured lift for stats.fm.

## Grounding

The screens, copy, artist bubbles, tour slides and the Pro paywall all come from the stats.fm iOS app as recorded on 13 November 2026 (EU storefront: €6.99, €9.99 and €14.99). The rating (4.6 from 48K ratings) and "15M+ users worldwide" come from the US App Store listing. That listing's purchase list shows no trial. The ad creatives and the Apple Ads share of voice are as AppMagic sees them.

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/.
