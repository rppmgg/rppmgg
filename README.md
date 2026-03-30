# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 19.4h | 24h | 24h | ~4,778h* |
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
| gpt-5.4 | 1,229 | 18.7M | 996K | 192.1M | $116.94 | $360.25 | $467.22 |
| **Total** | **1,229** | **18.7M** | **996K** | **192.1M** | **$116.94** | **$360.25** | **$467.22** |

_211.8M total tokens processed. 90.7% cache hit rate._

_$827.47 total saved ($360.25 caching + $467.22 model routing vs all-Opus)._

_Model savings are modest because ~90.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 2,036 | 26.8M | 1.3M | 272.6M | $251.21 | $511.30 | $662.94 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **2,381** | **26.9M** | **1.5M** | **309.0M** | **$317.33** | **$998.17** | **$663.94** |

_339.5M total tokens processed. 91% cache hit rate._

_$1,662.11 total saved ($998.17 caching + $663.94 model routing vs all-Opus)._

_Model savings are modest because ~91% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-30 17:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
