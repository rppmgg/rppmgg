# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 23.7h | 24h | 24h | ~4,672h* |
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
| gpt-5.4 | 65 | 1.0M | 62K | 7.2M | $5.93 | $13.55 | $23.87 |
| **Total** | **65** | **1.0M** | **62K** | **7.2M** | **$5.93** | **$13.55** | **$23.87** |

_8.3M total tokens processed. 86.4% cache hit rate._

_$37.42 total saved ($13.55 caching + $23.87 model routing vs all-Opus)._

_Model savings are modest because ~86.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 872 | 9.2M | 425K | 87.7M | $82.12 | $164.60 | $219.59 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **1,217** | **9.2M** | **584K** | **124.1M** | **$148.24** | **$651.47** | **$220.59** |

_135.9M total tokens processed. 91.3% cache hit rate._

_$872.05 total saved ($651.47 caching + $220.59 model routing vs all-Opus)._

_Model savings are modest because ~91.3% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-26 15:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
