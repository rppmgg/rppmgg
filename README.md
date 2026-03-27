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
| gpt-5.4 | 462 | 8.2M | 416K | 84.0M | $50.77 | $157.66 | $204.27 |
| **Total** | **462** | **8.2M** | **416K** | **84.0M** | **$50.77** | **$157.66** | **$204.27** |

_92.7M total tokens processed. 90.6% cache hit rate._

_$361.93 total saved ($157.66 caching + $204.27 model routing vs all-Opus)._

_Model savings are modest because ~90.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,269 | 16.4M | 779K | 164.6M | $151.74 | $308.71 | $399.99 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **1,614** | **16.4M** | **937K** | **201.0M** | **$217.86** | **$795.57** | **$400.99** |

_220.4M total tokens processed. 91.2% cache hit rate._

_$1,196.56 total saved ($795.57 caching + $400.99 model routing vs all-Opus)._

_Model savings are modest because ~91.2% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-27 19:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
