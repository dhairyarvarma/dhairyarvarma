<img src="assets/banner.svg" width="100%" alt="dhairyarvarma. Built to hold up. Backend engineering, with failure in mind." />

<p align="center">
  <img src="assets/focus.svg" width="640" alt="Backend systems. Thoughtful design. Failure-aware engineering." />
</p>

I’m **dhairyarvarma**. I’m building backend systems and exploring the decisions that make them reliable: where state lives, when work is retried, and how a system recovers after a crash.

My current focus is **Go, durable queues, and failure recovery**. I like following a request beyond the happy path — through the queue, the retry, and the restart.

<p>
  <a href="https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public"><img src="https://img.shields.io/badge/BUILDING-Webhook%20Delivery-24262b?style=flat-square&amp;labelColor=24262b&amp;color=8b5cf6" alt="Building: Webhook Delivery" /></a>
  <a href="https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/actions"><img src="https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/actions/workflows/ci.yml/badge.svg" alt="Project CI status" /></a>
</p>

<br />

### In focus

#### [Fault-Tolerant Webhook Delivery Engine ↗](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public)

An asynchronous webhook backend built around a simple requirement: accepted work needs a durable path to delivery, even when individual components fail.

PostgreSQL owns the durable state. A transactional outbox feeds Redis Streams. Workers handle delivery with bounded retries, per-target circuit breakers, and dead-letter replay.

> At-least-once delivery, with idempotency protection. The interesting part is what happens between attempts.

[Take the five-minute tour](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/showcase.md) &nbsp; / &nbsp; [Follow a worker crash](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/case-study-delivery-crash.md) &nbsp; / &nbsp; [Read the code](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public)

<img src="assets/delivery-path.svg" width="100%" alt="Delivery architecture: API commits an event and outbox record in PostgreSQL; the outbox relay sends work to Redis Streams; workers deliver to receivers and persist results in PostgreSQL. The moving dot is illustrative, not live telemetry." />

<br />

### Engineering notebook

<table>
<tr>
<td width="50%" valign="top">

#### 01 / When a worker disappears

What happens if a receiver accepts a request but the worker crashes before recording success? Follow the boundary between a durable event and an external side effect.

[Read the recovery case study ↗](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/case-study-delivery-crash.md)

</td>
<td width="50%" valign="top">

#### 02 / The delivery contract

Queues, retries, and idempotency have different jobs. The system’s guarantees start with being explicit about what each one can promise.

[Explore the delivery semantics ↗](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/QUEUE_AND_DELIVERY_SEMANTICS.md)

</td>
</tr>
</table>

### On my workbench

<p>
  <img src="https://skillicons.dev/icons?i=go,postgres,redis,docker,prometheus,grafana,git,github&amp;theme=dark&amp;perline=8" alt="Go, PostgreSQL, Redis, Docker, Prometheus, Grafana, Git, and GitHub" />
</p>

**Build** &nbsp; Go · PostgreSQL · Redis &nbsp; / &nbsp; **Run & inspect** &nbsp; Docker · Prometheus · Grafana

<sub>Tools used in my current project, rather than a self-rated skills chart.</sub>

<br />

### Principles behind the code

**Keep the state durable.** &nbsp; **Make failures visible.** &nbsp; **Document the tradeoffs.**

---

### The contribution trail

<sub>A little motion between builds. Refreshed daily by GitHub Actions.</sub>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake.svg" width="100%" alt="A snake following dhairyarvarma's contribution history" />
</picture>

<p align="right"><sub>Always a work in progress. Built with intent.</sub></p>
