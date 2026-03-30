# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 6.4h | 24h | 24h | ~4,789h* |
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
| gpt-5.4 | 1,045 | 15.9M | 838K | 162.0M | $98.75 | $303.79 | $395.14 |
| **Total** | **1,045** | **15.9M** | **838K** | **162.0M** | **$98.75** | **$303.79** | **$395.14** |

_178.7M total tokens processed. 90.6% cache hit rate._

_$698.93 total saved ($303.79 caching + $395.14 model routing vs all-Opus)._

_Model savings are modest because ~90.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,853 | 24.0M | 1.2M | 242.5M | $223.72 | $454.83 | $590.86 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **2,198** | **24.0M** | **1.3M** | **278.9M** | **$289.84** | **$941.70** | **$591.86** |

_306.3M total tokens processed. 91.1% cache hit rate._

_$1,533.56 total saved ($941.70 caching + $591.86 model routing vs all-Opus)._

_Model savings are modest because ~91.1% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-30 04:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
