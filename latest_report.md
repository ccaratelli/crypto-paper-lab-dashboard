# Paper-only research dashboard

**Generated:** 2026-09-08T00:33:22+00:00  
**As-of close:** 2026-09-07  
**Safety boundary:** simulated EUR portfolio only; no account connection or order submission exists.

## Portfolio

| Metric | Value |
| --- | --- |
| Virtual equity | €9,985.18 |
| Starting budget | €10,000.00 |
| Daily return | -0.55% |
| Cash | €5,664.67 |
| As-of close | 2026-09-07 |
| Mode | Paper only — no order route |

## Fixed paper sleeves

`trend_20_60`, `trend_50_150`, `momentum_90`

## Walk-forward evidence — standard view

| Strategy | Return | Max drawdown | Score | Days |
| --- | --- | --- | --- | --- |
| Trend 20/60 | +9.89% | -12.82% | -15.75% | 181 |
| Trend 50/150 | -5.39% | -7.02% | -19.43% | 181 |
| Relative momentum 90d | -3.82% | -7.96% | -19.74% | 181 |
| Defensive equal weight | +11.36% | -18.42% | -25.47% | 181 |

## Daily system hypotheses

| Hypothesis | Status | Claim |
| --- | --- | --- |
| data_integrity_is_sufficient | supported | The daily system should only study completed, independently validated closes. |
| costs_do_not_reverse_findings | observing | Candidate conclusions should be inspected under twice the configured trading costs. |
| results_are_not_single_window_artifacts | observing | Recent 90-day evidence should not silently replace the 180-day evidence. |
| active_sleeves_remain_benchmark_accountable | observing | Active paper sleeves must be measured against a capped equal-weight comparator after costs. |
| tail_risk_is_measured_under_dependence_and_execution_stress | observing_not_a_trade_instruction | Observed returns should be examined under dependence, gap, and impaired-exit sensitivity without assuming a perfect stop fill. |
| pre_registered_challengers_require_robustness_checks | observing | Risk-overlay variants must be pre-registered, isolated, cost-stressed, and checked for selection fragility before review. |
| hourly_stop_latency_is_observation_only | observation_only_not_an_execution_model | Validated hourly closes can quantify a delayed-close stop proxy but cannot guarantee an intraday exit or liquidity. |

## Research diary — public-safe evidence log

Each dated entry records what was tested, the result, and why the mandate did not change. Results are observations, not investment instructions or forecasts.

| Date | What ran | Finding | Risk / challenger result | Decision |
| --- | --- | --- | --- | --- |
| 2026-09-07 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+9.89%); capped equal weight returned +11.36%. | The two-day impaired-exit sensitivity ended below its starting value in 76.57% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-06 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+9.24%); capped equal weight returned +11.43%. | The two-day impaired-exit sensitivity ended below its starting value in 80.10% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-05 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+8.85%); capped equal weight returned +12.52%. | The two-day impaired-exit sensitivity ended below its starting value in 82.20% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |

## Pre-registered challenger evidence

| Experiment | Status | Decision / claim |
| --- | --- | --- |
| volatility_target_12pct | rejected_by_pre_registered_gates | Remain a negative result; do not alter fixed paper sleeves. |
| volatility_target_12pct_drawdown_guard | rejected_by_pre_registered_gates | Remain a negative result; do not alter fixed paper sleeves. |
| volatility_target_12pct | ready_for_isolated_evaluation | Scaling down exposure when realised volatility is elevated may improve drawdown without sacrificing too much return. |
| volatility_target_12pct_drawdown_guard | ready_for_isolated_evaluation | A capped de-risking overlay after a material sleeve drawdown may reduce tail loss beyond volatility scaling alone. |

## Selection-fragility diagnostics — observation only

| Metric | Value |
| --- | --- |
| CSCV-style status | observing_not_a_promotion_rule |
| CSCV estimated selection fragility | +23.02% |
| CSCV variants / observations | 3 / 180 |
| Deflated-Sharpe status | observing_not_a_promotion_rule |
| Multiple-testing trials counted | 3 |
| Sharpe exceeds trial hurdle | +18.35% |
| Rejected challenger results | 2 |

## Hourly stop-latency research — observation only

| Metric | Value |
| --- | --- |
| Study status | observation_only_not_an_execution_model |
| Validated hourly observations | 720 |
| Stop proxy | +3.00% / 24h horizon |
| Worst next-hour gap vs stop | -1.12% |
| Method | hourly_close_trigger_then_next_completed_hour_close_exit |

## Tail-risk diagnostics — observation only

| Metric | Value |
| --- | --- |
| Diagnostic status | observing_not_a_trade_instruction |
| Cost-aware max drawdown | -9.20% |
| Annualized volatility | +9.21% |
| Worst observed daily return | -2.25% |
| Historical CVaR (worst 5% days) | -1.06% |
| Bootstrap paths / horizon | 3000 / 365 days |
| Standard: chance of ending loss | +47.47% |
| Standard: chance ending below 50% | +0.00% |
| Gap stress: chance of ending loss | +60.33% |
| Gap stress: chance ending below 50% | +0.00% |
| Gap stress: chance near zero | +0.00% |
| Two-day dislocation: chance ending loss | +76.57% |
| Two-day dislocation: chance ending below 50% | +0.00% |
| Two-day dislocation: chance near zero | +0.00% |

## Data validation

| Check | Value |
| --- | --- |
| Canonical | Kraken public OHLC API |
| Reference | Coinbase Exchange public candles API |
| Completed observations | 720 |
| Latest completed candle | 2026-09-07 |
| BTC-EUR cross-source deviation | +0.06% |
| ETH-EUR cross-source deviation | +0.07% |

## Interpretation

Research rankings are diagnostic evidence only. They cannot rotate paper sleeves, change risk limits, add assets, or authorise live trading.

