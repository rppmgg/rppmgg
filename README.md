# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 7.4h | 24h | 24h | ~4,789h* |
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
| gpt-5.4 | 1,162 | 17.0M | 942K | 177.2M | $107.65 | $332.31 | $428.88 |
| **Total** | **1,162** | **17.0M** | **942K** | **177.2M** | **$107.65** | **$332.31** | **$428.88** |

_195.1M total tokens processed. 90.8% cache hit rate._

_$761.19 total saved ($332.31 caching + $428.88 model routing vs all-Opus)._

_Model savings are modest because ~90.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,970 | 25.1M | 1.3M | 257.7M | $236.99 | $483.36 | $624.59 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **2,315** | **25.1M** | **1.4M** | **294.1M** | **$303.11** | **$970.23** | **$625.59** |

_322.8M total tokens processed. 91.1% cache hit rate._

_$1,595.82 total saved ($970.23 caching + $625.59 model routing vs all-Opus)._

_Model savings are modest because ~91.1% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-30 05:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
