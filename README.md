# 🏁 Car Ratings by Fable

**A lifetime car-experience leaderboard.** Log every car you drive with the 6-question **Gut-Check Scorecard**, get an instant star rating, and watch the leaderboard re-rank itself.

Built as a **PWA** - installs to the home screen on both **iPhone** and **Android** and works offline.

## The Gut-Check Scorecard

**6 rapid-fire questions. Score each 1-3. Zero homework.**

| Score | Meaning |
|---|---|
| **1 - Nah** | Boring, fake, or video-game feel |
| **2 - Good** | Fun, but missing something / felt isolated |
| **3 - Holy Hell!** | Goosebumps. Unforgettable. Pure physical feedback |

**Half-points are legal.** When a car genuinely sits between two grades, tap the
smaller dashed **1.5** or **2.5** button between them. They are deliberately
secondary - the eye still lands on 1 / 2 / 3 first, so the gut-check stays fast.
Use them when the honest answer is "between", not to avoid committing.

**Questions 1-4 (universal):** Steering Feel / Shifting / Noise / Cockpit Tactility
**Questions 5-6 (segment-specific):** chassis character + track/braking intent, worded per tab.

**The math:** Total (max 18) / 3.6 = star rating out of 5.0

| Stars | Tier |
|---|---|
| ~5.0 | Analog Immortal |
| ~4.0 | Precision Weapon |
| ~3.0 | Optimized Commuter |
| <2.0 | Appliance |

## Features (MVP)

- **Dynamic leaderboard** - auto-ranks by stars, medal badges for top 3
- **Segment tabs** - All / Supercar / Sports Car / GT Car / Other
- **Instant scorecard** - big tap targets, live total/stars/tier as you answer
- **Memory-jogger notes** per car, one tap away
- **Retest flags** - mark provisional scores (e.g. forced-auto track days)
- **Data-integrity flags** surfaced right on the card
- **Export / Import JSON backup** (menu, top right)
- **Offline-first** via service worker; data stored on-device

## Run it

Any static host works. GitHub Pages serves it from the repo root.

Local test: python3 -m http.server 8000 then open http://localhost:8000.

## Install to phone

- **iPhone (Safari):** Share -> **Add to Home Screen**
- **Android (Chrome):** Menu -> **Add to Home screen / Install app**

---

*Seeded with the original three-car track shootout: Mercedes-AMG GT R / Porsche 911 GT3 / Chevrolet Corvette C8.*
