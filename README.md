# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 24h | 24h | 24h | ~4,771h* |
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
| gpt-5.4 | 513 | 9.2M | 446K | 96.9M | $56.91 | $181.69 | $229.08 |
| **Total** | **513** | **9.2M** | **446K** | **96.9M** | **$56.91** | **$181.69** | **$229.08** |

_106.5M total tokens processed. 90.9% cache hit rate._

_$410.77 total saved ($181.69 caching + $229.08 model routing vs all-Opus)._

_Model savings are modest because ~90.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,320 | 17.3M | 809K | 177.4M | $162.37 | $332.74 | $424.80 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **1,665** | **17.3M** | **968K** | **213.8M** | **$228.49** | **$819.60** | **$425.80** |

_234.1M total tokens processed. 91.3% cache hit rate._

_$1,245.40 total saved ($819.60 caching + $425.80 model routing vs all-Opus)._

_Model savings are modest because ~91.3% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-28 00:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
