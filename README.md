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
| gpt-5.4 | 412 | 5.8M | 397K | 72.4M | $41.46 | $135.76 | $162.67 |
| **Total** | **412** | **5.8M** | **397K** | **72.4M** | **$41.46** | **$135.76** | **$162.67** |

_78.6M total tokens processed. 92% cache hit rate._

_$298.43 total saved ($135.76 caching + $162.67 model routing vs all-Opus)._

_Model savings are modest because ~92% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,219 | 14.0M | 760K | 152.9M | $138.21 | $286.80 | $358.39 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **1,564** | **14.0M** | **919K** | **189.3M** | **$204.33** | **$773.67** | **$359.39** |

_206.3M total tokens processed. 91.8% cache hit rate._

_$1,133.06 total saved ($773.67 caching + $359.39 model routing vs all-Opus)._

_Model savings are modest because ~91.8% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-27 04:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
