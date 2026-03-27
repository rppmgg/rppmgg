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
| gpt-5.4 | 188 | 1.7M | 209K | 21.0M | $14.18 | $39.42 | $53.47 |
| **Total** | **188** | **1.7M** | **209K** | **21.0M** | **$14.18** | **$39.42** | **$53.47** |

_22.9M total tokens processed. 91.6% cache hit rate._

_$92.89 total saved ($39.42 caching + $53.47 model routing vs all-Opus)._

_Model savings are modest because ~91.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 995 | 9.8M | 573K | 101.5M | $93.81 | $190.47 | $249.19 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **1,340** | **9.8M** | **731K** | **137.9M** | **$159.93** | **$677.33** | **$250.19** |

_150.5M total tokens processed. 91.6% cache hit rate._

_$927.52 total saved ($677.33 caching + $250.19 model routing vs all-Opus)._

_Model savings are modest because ~91.6% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-27 00:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
