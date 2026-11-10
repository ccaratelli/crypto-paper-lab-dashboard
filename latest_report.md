# Paper-only research dashboard

**Generated:** 2026-11-10T01:31:49+00:00  
**As-of close:** 2026-11-09  
**Safety boundary:** simulated EUR portfolio only; no account connection or order submission exists.

## Portfolio

| Metric | Value |
| --- | --- |
| Virtual equity | €9,685.73 |
| Starting budget | €10,000.00 |
| Daily return | -0.11% |
| Cash | €6,640.37 |
| As-of close | 2026-11-09 |
| Mode | Paper only — no order route |

## Fixed paper sleeves

`trend_20_60`, `trend_50_150`, `momentum_90`

## Walk-forward evidence — standard view

| Strategy | Return | Max drawdown | Score | Days |
| --- | --- | --- | --- | --- |
| Trend 20/60 | +2.23% | -11.95% | -21.66% | 181 |
| Relative momentum 90d | -8.59% | -9.36% | -27.31% | 181 |
| Trend 50/150 | -8.42% | -10.50% | -29.42% | 181 |
| Defensive equal weight | +0.36% | -17.60% | -34.84% | 181 |

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
| 2026-11-09 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+2.23%); capped equal weight returned +0.36%. | The two-day impaired-exit sensitivity ended below its starting value in 90.60% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-11-08 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+1.65%); capped equal weight returned +1.79%. | The two-day impaired-exit sensitivity ended below its starting value in 87.93% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-11-07 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+0.57%); capped equal weight returned +0.66%. | The two-day impaired-exit sensitivity ended below its starting value in 89.53% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-11-06 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (-0.05%); capped equal weight returned -0.30%. | The two-day impaired-exit sensitivity ended below its starting value in 90.47% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-11-05 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+1.14%); capped equal weight returned +4.98%. | The two-day impaired-exit sensitivity ended below its starting value in 82.00% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-11-02 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (-0.24%); capped equal weight returned +1.81%. | The two-day impaired-exit sensitivity ended below its starting value in 87.40% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-11-01 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (-0.72%); capped equal weight returned +1.10%. | The two-day impaired-exit sensitivity ended below its starting value in 89.50% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-30 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+0.83%); capped equal weight returned +2.54%. | The two-day impaired-exit sensitivity ended below its starting value in 86.90% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-27 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+3.58%); capped equal weight returned +6.19%. | The two-day impaired-exit sensitivity ended below its starting value in 81.53% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-24 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+3.74%); capped equal weight returned +6.24%. | The two-day impaired-exit sensitivity ended below its starting value in 78.10% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-22 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+5.36%); capped equal weight returned +7.90%. | The two-day impaired-exit sensitivity ended below its starting value in 70.47% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-20 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+3.25%); capped equal weight returned +5.74%. | The two-day impaired-exit sensitivity ended below its starting value in 78.07% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-18 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+4.04%); capped equal weight returned +6.55%. | The two-day impaired-exit sensitivity ended below its starting value in 77.87% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-15 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+4.64%); capped equal weight returned +7.16%. | The two-day impaired-exit sensitivity ended below its starting value in 76.20% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-13 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+5.61%); capped equal weight returned +8.16%. | The two-day impaired-exit sensitivity ended below its starting value in 72.57% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-11 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+7.47%); capped equal weight returned +10.06%. | The two-day impaired-exit sensitivity ended below its starting value in 67.20% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-10 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+6.21%); capped equal weight returned +8.78%. | The two-day impaired-exit sensitivity ended below its starting value in 69.93% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-09 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+9.25%); capped equal weight returned +11.89%. | The two-day impaired-exit sensitivity ended below its starting value in 65.40% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-08 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+9.12%); capped equal weight returned +11.76%. | The two-day impaired-exit sensitivity ended below its starting value in 60.90% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-10-04 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+11.83%); capped equal weight returned +14.53%. | The two-day impaired-exit sensitivity ended below its starting value in 47.97% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-23 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+17.81%); capped equal weight returned +20.65%. | The two-day impaired-exit sensitivity ended below its starting value in 35.73% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-22 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+16.78%); capped equal weight returned +18.71%. | The two-day impaired-exit sensitivity ended below its starting value in 36.87% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-19 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+12.08%); capped equal weight returned +11.89%. | The two-day impaired-exit sensitivity ended below its starting value in 59.70% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-18 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+8.13%); capped equal weight returned +10.65%. | The two-day impaired-exit sensitivity ended below its starting value in 80.83% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-15 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+9.34%); capped equal weight returned +9.69%. | The two-day impaired-exit sensitivity ended below its starting value in 75.23% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-13 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+8.88%); capped equal weight returned +4.65%. | The two-day impaired-exit sensitivity ended below its starting value in 76.77% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-09 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+8.62%); capped equal weight returned +8.38%. | The two-day impaired-exit sensitivity ended below its starting value in 80.37% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-08 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+8.97%); capped equal weight returned +9.81%. | The two-day impaired-exit sensitivity ended below its starting value in 80.07% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-07 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+9.89%); capped equal weight returned +11.36%. | The two-day impaired-exit sensitivity ended below its starting value in 76.57% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |
| 2026-09-06 | Validated completed BTC-EUR and ETH-EUR daily closes; reran the fixed, cost-aware walk-forward protocol; kept the paper sleeves unchanged. | Best active-sleeve 180-day diagnostic return was Trend 20/60 (+9.24%); capped equal weight returned +11.43%. | The two-day impaired-exit sensitivity ended below its starting value in 80.10% of resampled paths; this is not a forecast. 2 of 2 pre-registered challengers were rejected by their fixed gates and remain isolated. | No mandate change: research cannot alter sleeves, limits, costs, assets, or create a live order route. |

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
| CSCV estimated selection fragility | +4.37% |
| CSCV variants / observations | 3 / 180 |
| Deflated-Sharpe status | observing_not_a_promotion_rule |
| Multiple-testing trials counted | 3 |
| Sharpe exceeds trial hurdle | +7.83% |
| Rejected challenger results | 2 |

## Hourly stop-latency research — observation only

| Metric | Value |
| --- | --- |
| Study status | observation_only_not_an_execution_model |
| Validated hourly observations | 720 |
| Stop proxy | +3.00% / 24h horizon |
| Worst next-hour gap vs stop | -4.70% |
| Method | hourly_close_trigger_then_next_completed_hour_close_exit |

## Tail-risk diagnostics — observation only

| Metric | Value |
| --- | --- |
| Diagnostic status | observing_not_a_trade_instruction |
| Cost-aware max drawdown | -8.76% |
| Annualized volatility | +13.91% |
| Worst observed daily return | -2.25% |
| Historical CVaR (worst 5% days) | -1.80% |
| Bootstrap paths / horizon | 3000 / 365 days |
| Standard: chance of ending loss | +77.47% |
| Standard: chance ending below 50% | +0.00% |
| Gap stress: chance of ending loss | +83.97% |
| Gap stress: chance ending below 50% | +0.00% |
| Gap stress: chance near zero | +0.00% |
| Two-day dislocation: chance ending loss | +90.60% |
| Two-day dislocation: chance ending below 50% | +0.00% |
| Two-day dislocation: chance near zero | +0.00% |

## Data validation

| Check | Value |
| --- | --- |
| Canonical | Kraken public OHLC API |
| Reference | Coinbase Exchange public candles API |
| Completed observations | 720 |
| Latest completed candle | 2026-11-09 |
| BTC-EUR cross-source deviation | +0.04% |
| ETH-EUR cross-source deviation | +0.10% |

## Interpretation

Research rankings are diagnostic evidence only. They cannot rotate paper sleeves, change risk limits, add assets, or authorise live trading.

