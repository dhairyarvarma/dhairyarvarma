<div align="center">

<img src="assets/banner.svg" width="100%" alt="dhairyarvarma — backend systems, durable by design" />

<br />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&amp;weight=500&amp;size=20&amp;pause=1400&amp;color=A78BFA&amp;center=true&amp;vCenter=true&amp;width=650&amp;lines=Building+backends+that+handle+failure.;Go+%2F+PostgreSQL+%2F+Redis;Make+it+durable.+Make+it+observable." alt="Building backends that handle failure. Go, PostgreSQL, Redis. Make it durable. Make it observable." />

[![GitHub](https://img.shields.io/badge/GitHub-dhairyarvarma-161b22?style=flat-square&logo=github&logoColor=white)](https://github.com/dhairyarvarma)
[![Explore my work](https://img.shields.io/badge/Explore-my_work-34d399?style=flat-square&logo=go&logoColor=black)](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public)

</div>

## `~/` whoami

```console
dhairyarvarma@github:~$ cat focus.txt
> Backend engineering. Durable data. Explicit failure handling.
> Currently building a fault-tolerant webhook delivery engine in Go.
> Following the event from the first request to the final delivery.
```

I build backend systems with a focus on what happens when things go wrong: a worker crashes, a receiver slows down, or a queue delivers the same message twice.

My current work brings together transactional outboxes, retries, circuit breakers, and observability in one webhook delivery backend.

## `~/` selected work

<table>
<tr>
<td width="50%" valign="top">

### ↗ Webhook Delivery Engine

A durable, asynchronous webhook backend. PostgreSQL holds the durable state; Redis Streams carries work to the workers.

Retries with backoff and jitter, per-target circuit breakers, dead-letter replay, and crash recovery. At-least-once delivery with idempotency protection.

`Go` `PostgreSQL` `Redis` `Docker`

[Explore the repository →](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public)

</td>
<td width="50%" valign="top">

### ⌁ Behind the Delivery

A closer look at the same system: the crash boundaries, durable state transitions, and recovery decisions behind a delivery attempt.

Start with the five-minute showcase, then follow the crash-recovery case study through the failure path.

`System design` `Recovery` `Observability`

[Read the showcase →](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/showcase.md) · [Crash case study →](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/case-study-delivery-crash.md)

</td>
</tr>
</table>

## `~/` tools in this build

<p align="center">
<img src="https://skillicons.dev/icons?i=go,postgres,redis,docker,prometheus,grafana,git,github&amp;theme=dark" alt="Go, PostgreSQL, Redis, Docker, Prometheus, Grafana, Git, and GitHub" />
</p>

## `~/` contribution trail

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake.svg" width="100%" alt="Animated snake tracing dhairyarvarma's GitHub contribution graph" />
</picture>

---

<p align="center"><sub>Make the failure path as deliberate as the happy path.</sub></p>
