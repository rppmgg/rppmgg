# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 8.9h | 27.8h | 107.6h | ~4,785h* |
| User AI session hours | 0.0h | 0.0h | 0.0h | 0.0h |
| AI worker hours | 0.0h | 0.0h | 0.0h | 0.0h |
| AI concurrency hours | 0.0h | 0.3h | 0.3h | 0.3h |
| Interactive sessions | 0 | 65 | 65 | 65 |
| Worker sessions | 0 | 0 | 0 | 0 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,268 | 19.5M | 1.0M | 201.9M | $122.02 | $378.64 | $487.90 |
| **Total** | **1,268** | **19.5M** | **1.0M** | **201.9M** | **$122.02** | **$378.64** | **$487.90** |

_222.5M total tokens processed. 90.7% cache hit rate._

_$866.53 total saved ($378.64 caching + $487.90 model routing vs all-Opus)._

_Model savings are modest because ~90.7% of tokens are cache reads, where price differences between models are small._

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
_Stats auto-updated 2026-04-17 20:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
