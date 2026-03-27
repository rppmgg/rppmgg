# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 23.3h | 24h | 24h | ~4,771h* |
| User AI session hours | 0.0h | 0.0h | 0.1h | 0.1h |
| AI worker hours | 0.0h | 0.0h | 0.0h | 0.0h |
| AI concurrency hours | 0.0h | 0.0h | 0.1h | 0.1h |
| Interactive sessions | 0 | 1 | 2 | 2 |
| Worker sessions | 0 | 0 | 0 | 0 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 425 | 6.8M | 402K | 74.9M | $44.63 | $140.56 | $177.40 |
| **Total** | **425** | **6.8M** | **402K** | **74.9M** | **$44.63** | **$140.56** | **$177.40** |

_82.2M total tokens processed. 91.2% cache hit rate._

_$317.96 total saved ($140.56 caching + $177.40 model routing vs all-Opus)._

_Model savings are modest because ~91.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,232 | 14.9M | 765K | 155.5M | $142.30 | $291.60 | $373.12 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **1,577** | **15.0M** | **923K** | **191.8M** | **$208.42** | **$778.47** | **$374.12** |

_209.8M total tokens processed. 91.5% cache hit rate._

_$1,152.59 total saved ($778.47 caching + $374.12 model routing vs all-Opus)._

_Model savings are modest because ~91.5% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-27 16:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
