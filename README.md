# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 15.4h | 24h | 24h | ~4,778h* |
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
| gpt-5.4 | 1,186 | 17.1M | 960K | 180.9M | $109.40 | $339.22 | $435.37 |
| **Total** | **1,186** | **17.1M** | **960K** | **180.9M** | **$109.40** | **$339.22** | **$435.37** |

_199.0M total tokens processed. 90.9% cache hit rate._

_$774.59 total saved ($339.22 caching + $435.37 model routing vs all-Opus)._

_Model savings are modest because ~90.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,993 | 25.3M | 1.3M | 261.4M | $239.90 | $490.27 | $631.09 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **2,338** | **25.3M** | **1.4M** | **297.8M** | **$306.02** | **$977.14** | **$632.09** |

_326.6M total tokens processed. 91.2% cache hit rate._

_$1,609.22 total saved ($977.14 caching + $632.09 model routing vs all-Opus)._

_Model savings are modest because ~91.2% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-30 13:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
