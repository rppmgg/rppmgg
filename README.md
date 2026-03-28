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
| Interactive sessions | 0 | 0 | 2 | 2 |
| Worker sessions | 0 | 0 | 0 | 0 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 807 | 12.5M | 646K | 129.3M | $77.89 | $242.52 | $311.93 |
| **Total** | **807** | **12.5M** | **646K** | **129.3M** | **$77.89** | **$242.52** | **$311.93** |

_142.5M total tokens processed. 90.7% cache hit rate._

_$554.44 total saved ($242.52 caching + $311.93 model routing vs all-Opus)._

_Model savings are modest because ~90.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,614 | 20.6M | 1.0M | 209.9M | $192.93 | $393.56 | $507.64 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **1,959** | **20.7M** | **1.1M** | **246.2M** | **$259.05** | **$880.43** | **$508.64** |

_270.1M total tokens processed. 91.2% cache hit rate._

_$1,389.07 total saved ($880.43 caching + $508.64 model routing vs all-Opus)._

_Model savings are modest because ~91.2% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-28 04:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
