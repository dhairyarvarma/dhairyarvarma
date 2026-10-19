<img src="assets/banner.svg" width="100%" alt="dhairyarvarma. Built to hold up. Backend engineering, with failure in mind." />

<br />

I’m **dhairyarvarma**. I’m building backend systems and exploring the decisions that make them reliable: where state lives, when work is retried, and how a system recovers after a crash.

My current focus is **Go, durable queues, and failure recovery**.

<br />

### In focus

#### [Fault-Tolerant Webhook Delivery Engine ↗](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public)

An asynchronous webhook backend built around a simple requirement: accepted work needs a durable path to delivery, even when individual components fail.

PostgreSQL owns the durable state. A transactional outbox feeds Redis Streams. Workers handle delivery with bounded retries, per-target circuit breakers, and dead-letter replay.

> At-least-once delivery, with idempotency protection. The interesting part is what happens between attempts.

[Take the five-minute tour](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/showcase.md) &nbsp; / &nbsp; [Follow a worker crash](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/case-study-delivery-crash.md) &nbsp; / &nbsp; [Read the code](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public)

<br />

### What I care about

**State that survives.** Keeping durable records separate from the transport that moves work.

**Failure you can explain.** Explicit transitions, observable attempts, and a recovery path you can trace.

**Design you can defend.** Clear guarantees, documented tradeoffs, and evidence behind the claims.

<br />

**Working with** &nbsp; Go · PostgreSQL · Redis · Docker · Prometheus · Grafana

---

<details>
<summary>The contribution snake</summary>
<br />
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake.svg" width="100%" alt="A snake following dhairyarvarma's contribution history" />
</picture>
</details>