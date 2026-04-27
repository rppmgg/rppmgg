# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 24h | 12.8h | 123.1h | ~4,844h* |
| User AI session hours | 0.0h | 0.0h | 0.0h | 0.0h |
| AI worker hours | 0.0h | 0.0h | 0.0h | 0.0h |
| AI concurrency hours | 0.0h | 0.0h | 0.2h | 0.2h |
| Interactive sessions | 0 | 0 | 50 | 50 |
| Worker sessions | 0 | 0 | 0 | 0 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 427 | 6.3M | 344K | 67.2M | $40.24 | $126.17 | $160.05 |
| **Total** | **427** | **6.3M** | **344K** | **67.2M** | **$40.24** | **$126.17** | **$160.05** |

_73.9M total tokens processed. 91% cache hit rate._

_$286.22 total saved ($126.17 caching + $160.05 model routing vs all-Opus)._

_Model savings are modest because ~91% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 2,075 | 27.7M | 1.3M | 282.4M | $259.68 | $529.68 | $683.61 |
| claude-opus-4-6 | 338 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **2,422** | **27.7M** | **1.5M** | **318.8M** | **$325.80** | **$1,016.55** | **$684.61** |

_350.1M total tokens processed. 91.1% cache hit rate._

_$1,701.16 total saved ($1,016.55 caching + $684.61 model routing vs all-Opus)._

_Model savings are modest because ~91.1% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-04-27 12:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
