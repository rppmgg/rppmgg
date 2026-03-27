# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 22.3h | 24h | 24h | ~4,771h* |
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
| gpt-5.4 | 422 | 6.5M | 400K | 74.4M | $43.76 | $139.53 | $173.34 |
| **Total** | **422** | **6.5M** | **400K** | **74.4M** | **$43.76** | **$139.53** | **$173.34** |

_81.3M total tokens processed. 91.4% cache hit rate._

_$312.87 total saved ($139.53 caching + $173.34 model routing vs all-Opus)._

_Model savings are modest because ~91.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,230 | 14.7M | 764K | 154.9M | $141.24 | $290.58 | $369.05 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **1,575** | **14.7M** | **922K** | **191.3M** | **$207.36** | **$777.44** | **$370.05** |

_209.0M total tokens processed. 91.6% cache hit rate._

_$1,147.50 total saved ($777.44 caching + $370.05 model routing vs all-Opus)._

_Model savings are modest because ~91.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-27 15:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
