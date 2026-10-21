<img src="assets/banner.svg" width="100%" alt="dhairyarvarma. Built to hold up. Full Stack Developer." />

<p align="center">
  <img src="assets/focus.svg" width="640" alt="Backend systems. Thoughtful design. Failure-aware engineering." />
</p>

I’m **dhairyarvarma**, a **Full Stack Developer** who enjoys turning an idea into a working product and making sure the system behind it holds up. I’m especially interested in how application code, data, and asynchronous work fit together.

On my workbench: a webhook delivery platform built with **Go, PostgreSQL, Redis, and Docker**. I follow each request from API to database to receiver, including retries, restarts, and the less predictable parts.

<p>
  <img src="https://img.shields.io/badge/ROLE-Full%20Stack%20Developer-8b5cf6?style=flat-square&amp;labelColor=24262b" alt="Role: Full Stack Developer" />
  <a href="https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public"><img src="https://img.shields.io/badge/BUILDING-Webhook%20Delivery-24262b?style=flat-square&amp;labelColor=24262b&amp;color=8b5cf6" alt="Building: Webhook Delivery" /></a>
  <a href="https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/actions"><img src="https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/actions/workflows/ci.yml/badge.svg" alt="Project CI status" /></a>
</p>

<br />

### Featured build

#### [Fault-Tolerant Webhook Delivery Engine ↗](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public)

A webhook delivery platform built around a simple promise: once an event is accepted, it has a durable path to its destination, even when parts of the system fail.

PostgreSQL owns the durable state. A transactional outbox feeds Redis Streams. Workers handle delivery with bounded retries, per-target circuit breakers, and dead-letter replay.

> At-least-once delivery, with idempotency protection. The interesting part is what happens between attempts.

[Take the five-minute tour](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/showcase.md) &nbsp; / &nbsp; [Follow a worker crash](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/case-study-delivery-crash.md) &nbsp; / &nbsp; [Read the code](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public)

<img src="assets/delivery-path.svg" width="100%" alt="Delivery architecture: API commits an event and outbox record in PostgreSQL; the outbox relay sends work to Redis Streams; workers deliver to receivers and persist results in PostgreSQL. The moving dot is illustrative, not live telemetry." />

<br />

### Design notes

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

### Tools I use

<p>
  <img src="https://skillicons.dev/icons?i=go,postgres,redis,docker,prometheus,grafana,git,github&amp;theme=dark&amp;perline=8" alt="Go, PostgreSQL, Redis, Docker, Prometheus, Grafana, Git, and GitHub" />
</p>

**Application** &nbsp; Go &nbsp; · &nbsp; **Data & queues** &nbsp; PostgreSQL · Redis &nbsp; · &nbsp; **Delivery & visibility** &nbsp; Docker · Prometheus · Grafana

<sub>Shown from the project I’m building.</sub>

<br />

### How I approach a build

<table><tr><td><b>01 · Understand the flow</b><br/>Map a request through the app and its dependencies.</td><td><b>02 · Plan for failure</b><br/>Decide how retries and recovery should work.</td><td><b>03 · Make it observable</b><br/>Leave enough evidence to explain what happened.</td></tr></table>

---

### GitHub activity

<sub>Contribution history · updated daily</sub>

<p align="center"><img src="https://github-readme-stats.vercel.app/api?username=dhairyarvarma&amp;show_icons=true&amp;hide_border=true&amp;bg_color=00000000&amp;title_color=a78bfa&amp;icon_color=a78bfa&amp;text_color=9b9da3" height="155" alt="GitHub activity summary" /></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake.svg" width="100%" alt="A snake following dhairyarvarma's contribution history" />
</picture>

<p align="right"><sub>Curious by default. Building one piece at a time.</sub></p>
