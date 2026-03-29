# rppmgg

> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 0.4h | 24h | 24h | ~4,789h* |
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
| gpt-5.4 | 916 | 14.7M | 730K | 149.9M | $90.39 | $281.18 | $362.70 |
| **Total** | **916** | **14.7M** | **730K** | **149.9M** | **$90.39** | **$281.18** | **$362.70** |

_165.4M total tokens processed. 90.7% cache hit rate._

_$643.88 total saved ($281.18 caching + $362.70 model routing vs all-Opus)._

_Model savings are modest because ~90.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.4 | 1,723 | 22.8M | 1.0M | 230.5M | $212.12 | $432.23 | $558.41 |
| claude-opus-4-6 | 336 | 351 | 156K | 36.0M | $65.78 | $486.21 | $0.00 |
| gpt-5.3-codex | 9 | 48K | 1K | 351K | $0.34 | $0.66 | $1.00 |
| **Total** | **2,068** | **22.8M** | **1.2M** | **266.8M** | **$278.24** | **$919.09** | **$559.41** |

_293.0M total tokens processed. 91.1% cache hit rate._

_$1,478.51 total saved ($919.09 caching + $559.41 model routing vs all-Opus)._

_Model savings are modest because ~91.1% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

<!-- UPDATED-START -->
_Stats auto-updated 2026-03-29 22:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
