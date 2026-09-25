# Car Ratings by Fable — changelog

## 2026-09-25
- **Connector write access verified.** Changes now push straight from Claude, no browser step.

## 2026-09-22
- **Tier cutoff confirmed.** Analog Immortal stays at 4.5+ and is earned by score, not reserved for the benchmark car. The AMG GT R holds #1 on stars (4.72 vs 4.58), not by owning a tier alone.

## 2026-09-09
- **Half-point scoring legalized.** 1.5 and 2.5 are valid. Half-steps render smaller and dashed in the scorecard so the eye still lands on 1 / 2 / 3 first and the gut-check stays fast.
- **C8 cockpit 2.5 ruled valid.** Its flag cleared; total (14.5) and stars (4.03) unchanged.
- **GT3 math flag resolved.** Its six scores summed to 17 while the logged total read 16.0 / 4.44 stars. Total, stars and tier all agreed with each other, so a single score was the likelier error. Steering dropped 3 → 2.5, the only GT3 dimension carrying a qualifier in the raw notes. GT3 is now 16.5 / 18 → 4.58 stars, and steering reads AMG 3 > GT3 2.5 > C8 2.
- Fixed a colour bug where 2.5 rendered green (`Math.round` rounds .5 up) instead of gold.

## Open
- **Shifting retest.** All three cars carry provisional 2s from a forced-auto track day. Every board position is under-rated on shifting until Tray re-runs them with manual paddle control.
