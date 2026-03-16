# Veri Asia — Performance Ledger

> **Last updated:** 2026-03-16 22:33 UTC
> **Model:** PV10 v7 Unified | **Markets:** DNB (Draw No Bet)
> **Leagues:** J-League, A-League, K-League 1, Saudi Pro League, Chinese Super League

---

## Brier Score & Skill Score

The [Brier Score](https://en.wikipedia.org/wiki/Brier_score) measures the accuracy of probabilistic predictions. Lower is better.
**Brier Skill Score (BSS)** = 1 − (Model Brier / Pinnacle Brier). Positive BSS means the model is more accurate than Pinnacle's closing line.

| League | Matches | Model Brier | Pinnacle Brier | BSS | |
|--------|---------|-------------|----------------|-----|---|
| A-League | 5 | 0.2651 | 0.2637 | -0.50% | ❌ |
| J.League | 11 | 0.2361 | 0.2241 | -5.36% | ❌ |
| K-League 1 | 2 | 0.1719 | 0.1887 | +8.93% | ✅ |
| Saudi Pro League | 15 | 0.1474 | 0.1442 | -2.22% | ❌ |
| **ALL** | **33** | **0.1963** | **0.1917** | **-2.42%** | ❌ |

> *Brier scores computed on 33 non-draw DNB matches out of 3255 total settled fixtures.*
> *Pinnacle closing line used as benchmark.*

---

## Closing Line Value (CLV)

CLV measures whether our locked prices beat Pinnacle's closing line — the sharpest benchmark in the market.

| Metric | Value |
|--------|-------|
| **Plays tracked** | 20 |
| **CLV-positive plays** | 9/20 (45% hit rate) |
| **Average CLV** | +0.24% |

> *A positive average CLV indicates consistently beating the closing line — the hallmark of a sharp bettor.*

---

## ROI & P/L

| League | Plays | Record | Staked | P/L (units) | ROI |
|--------|-------|--------|--------|-------------|-----|
| A-League | 3 | 1W 1L 1P | 3.0 | +3.31 | +110.3% |
| J.League | 9 | 3W 3L 3P | 10.0 | +2.06 | +20.6% |
| Saudi Pro League | 8 | 2W 5L 1P | 6.5 | +0.29 | +4.5% |
| **ALL** | **20** | **6W 9L 5P** | **19.5** | **+5.66** | **+29.0%** |

| **Avg odds** | 3.95 | | | |

> *All plays are 1 unit flat stake on DNB markets. P/L is net of stake.*

---

## Play Log

Full play-by-play history is available in [`plays.csv`](plays.csv).

| Date | League | Match | Side | Locked | Close | CLV | Result | P/L |
|------|--------|-------|------|--------|-------|-----|--------|-----|
| 2026-03-04 | A-League | Macarthur vs Central Coast Mariners | away | 3.87 | 4.07 | -4.9% | ✅ profit | +4.31 |
| 2026-03-06 | Saudi Pro League | Al Hilal vs Al Najma | away | 18.76 | 20.73 | -9.5% | ❌ loss | -0.50 |
| 2026-03-06 | Saudi Pro League | Al Khaleej vs Al Hazm | home | 1.52 | 1.46 | +4.1% | ✅ profit | +0.52 |
| 2026-03-07 | A-League | Newcastle United Jets vs Western Sydney Wanderers | away | 2.41 | 2.28 | +5.7% | ❌ loss | -1.00 |
| 2026-03-07 | J.League | FC Tokyo vs Yokohama F. Marinos | home | 1.53 | 1.49 | +2.7% | ✅ profit | +0.53 |
| 2026-03-07 | J.League | Cerezo Osaka vs Shimizu S-Pulse | away | 2.29 | 2.56 | -10.6% | ➖ push | +0.00 |
| 2026-03-07 | Saudi Pro League | Al Ettifaq vs Al Shabab | home | 2.41 | 2.42 | -0.4% | ➖ push | +0.00 |
| 2026-03-08 | A-League | Auckland vs Perth Glory | away | 5.85 | 5.84 | +0.2% | ➖ push | +0.00 |
| 2026-03-08 | J.League | Fagiano Okayama FC vs Kyoto Sanga | home | 2.62 | 2.67 | -1.9% | ✅ profit | +2.43 |
| 2026-03-08 | J.League | Gamba Osaka vs V-Varen Nagasaki | away | 2.65 | 2.66 | -0.4% | ❌ loss | -1.00 |
| 2026-03-12 | Saudi Pro League | Al Hazm vs Al Kholood | away | 2.02 | 1.81 | +11.6% | ❌ loss | -1.00 |
| 2026-03-12 | Saudi Pro League | Al Najma vs Damac FC | home | 2.64 | 2.19 | +20.6% | ❌ loss | -1.00 |
| 2026-03-13 | Saudi Pro League | Al Riyadh vs Al Ittihad | home | 4.27 | 4.11 | +3.9% | ✅ profit | +3.27 |
| 2026-03-14 | J.League | Nagoya Grampus vs Vissel Kobe | home | 2.42 | 2.33 | +3.9% | ❌ loss | -1.00 |
| 2026-03-14 | J.League | Tokyo Verdy vs Urawa Red Diamonds | home | 2.40 | 2.60 | -7.7% | ✅ profit | +2.10 |
| 2026-03-14 | J.League | Shimizu S-Pulse vs Fagiano Okayama FC | home | 1.75 | 1.74 | +0.6% | ➖ push | +0.00 |
| 2026-03-14 | J.League | Kyoto Sanga vs Cerezo Osaka | home | 1.58 | 1.66 | -4.8% | ❌ loss | -1.00 |
| 2026-03-14 | J.League | Mito Hollyhock vs FC Tokyo | home | 2.49 | 2.69 | -7.4% | ➖ push | +0.00 |
| 2026-03-14 | Saudi Pro League | Al Fateh vs Al Hilal | home | 9.01 | 9.01 | +0.0% | ❌ loss | -0.50 |
| 2026-03-14 | Saudi Pro League | Al Khaleej vs Al Nassr | home | 6.42 | 6.47 | -0.8% | ❌ loss | -0.50 |

---

## Methodology

- **Model:** PV10 v7 Unified — four-pillar performance rating (Finishing, Creation, Progression, Defensive) with weighted logistic probability model.
- **Market:** Draw No Bet (DNB) — Pinnacle lines used as the sharp benchmark.
- **Value threshold:** Plays are locked when the model identifies ≥ edge vs market.
- **Benchmark:** Pinnacle closing line — widely regarded as the sharpest odds in the market.
- **Brier Score:** Computed on all non-draw settled matches where both model and Pinnacle probabilities are available.

---

*This ledger is auto-generated from [`build_ledger.py`](https://github.com/veriasia/engine). Data sourced from Sportmonks and The Odds API.*
