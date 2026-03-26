# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 24h | 24h | 24h | ~4,767h* |
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
| gpt-5.4 | 128 | 1.3M | 120K | 10.7M | $8.73 | $20.19 | $33.63 |
| **Total** | **128** | **1.3M** | **120K** | **10.7M** | **$8.73** | **$20.19** | **$33.63** |

_12.1M total tokens processed. 88.3% cache hit rate._

_$53.82 total saved ($20.19 caching + $33.63 model routing vs all-Opus)._

_Model savings are modest because ~88.3% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 935 | 9.4M | 483K | 91.3M | $85.49 | $171.24 | $229.34 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **1,280** | **9.4M** | **642K** | **127.6M** | **$151.61** | **$658.11** | **$230.34** |

_139.8M total tokens processed. 91.3% cache hit rate._

_$888.45 total saved ($658.11 caching + $230.34 model routing vs all-Opus)._

_Model savings are modest because ~91.3% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-26 23:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
