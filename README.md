# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 21.3h | 24h | 24h | ~4,771h* |
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
| gpt-5.4 | 420 | 6.3M | 399K | 74.1M | $42.99 | $139.02 | $169.63 |
| **Total** | **420** | **6.3M** | **399K** | **74.1M** | **$42.99** | **$139.02** | **$169.63** |

_80.8M total tokens processed. 91.7% cache hit rate._

_$308.65 total saved ($139.02 caching + $169.63 model routing vs all-Opus)._

_Model savings are modest because ~91.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,227 | 14.4M | 763K | 154.7M | $140.38 | $290.07 | $365.35 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **1,572** | **14.4M** | **921K** | **191.0M** | **$206.50** | **$776.94** | **$366.35** |

_208.4M total tokens processed. 91.7% cache hit rate._

_$1,143.28 total saved ($776.94 caching + $366.35 model routing vs all-Opus)._

_Model savings are modest because ~91.7% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-27 14:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
