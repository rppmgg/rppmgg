# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 18.4h | 24h | 24h | ~4,778h* |
| User AI session hours | 0.0h | 0.0h | 0.1h | 0.1h |
| AI worker hours | 0.0h | 0.0h | 0.0h | 0.0h |
| AI concurrency hours | 0.0h | 0.0h | 0.1h | 0.1h |
| Interactive sessions | 0 | 0 | 2 | 2 |
| Worker sessions | 0 | 0 | 0 | 0 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,216 | 18.1M | 989K | 188.3M | $114.41 | $353.12 | $456.29 |
| **Total** | **1,216** | **18.1M** | **989K** | **188.3M** | **$114.41** | **$353.12** | **$456.29** |

_207.4M total tokens processed. 90.8% cache hit rate._

_$809.42 total saved ($353.12 caching + $456.29 model routing vs all-Opus)._

_Model savings are modest because ~90.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 2,024 | 26.3M | 1.3M | 268.8M | $247.33 | $504.17 | $652.01 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **2,369** | **26.3M** | **1.5M** | **305.2M** | **$313.45** | **$991.04** | **$653.01** |

_335.1M total tokens processed. 91.1% cache hit rate._

_$1,644.05 total saved ($991.04 caching + $653.01 model routing vs all-Opus)._

_Model savings are modest because ~91.1% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-30 16:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
