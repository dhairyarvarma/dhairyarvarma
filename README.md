<p align="center">
  <img src="assets/comic-hero.svg" width="100%" alt="Pixel-art night city with Spider-Man swinging on a web. Dhairyarvarma: build the whole thing. Full Stack Developer." />
</p>

<p align="center">
  <strong>Dhairya Varma</strong> · Full Stack Developer<br/>
  From a useful interface to the systems that make it work.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/NOW%20BUILDING-RepoScope-a78bfa?style=for-the-badge&amp;labelColor=171223" alt="Now building RepoScope" />
  <a href="https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public"><img src="https://img.shields.io/badge/EXPLORE-Webhook%20Engine-8b5cf6?style=for-the-badge&amp;labelColor=171223" alt="Explore the public webhook engine" /></a>
</p>

---

## ◈ Current mission / RepoScope

**What if a code review showed not only what changed, but what that change might affect?**

RepoScope is my current project: a local Python tool that compares committed revisions, traces static import evidence, and ranks candidate tests with reasons you can inspect in a browser UI. It reads source without running it or uploading it. I’m shaping it as a practical way to explore impact while keeping uncertainty visible.

| Status | Stack | Focus |
| :-- | :-- | :-- |
| Local MVP · private repository | Python · Git · HTML/CSS/JavaScript | Change impact · test selection · clear evidence |

<sub>The repository is private while I continue working on it. This section describes the project; it does not link to private source.</sub>

## ◈ Shipped work / Webhook Delivery Engine

A durable delivery system for the messy gap between accepting a webhook event and reaching the receiver. PostgreSQL holds event and outbox state; Redis Streams moves work; workers handle retries, circuit breakers, and replay.

**The contract:** at-least-once delivery with idempotency protection. I document the edge cases instead of hiding them behind a success message.

[View the public repository ↗](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public) &nbsp; · &nbsp; [Five-minute walkthrough ↗](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/showcase.md) &nbsp; · &nbsp; [Crash-recovery case study ↗](https://github.com/dhairyarvarma/fault-tolerant-webhook-dispatcher-public/blob/main/docs/case-study-delivery-crash.md)

---

## ◈ My toolkit

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,js,html,css,postgres,redis,docker,git,github&amp;theme=dark&amp;perline=10" alt="Python, Go, JavaScript, HTML, CSS, PostgreSQL, Redis, Docker, Git, and GitHub" />
</p>

| Build the experience | Make it work | Understand it in production |
| :-- | :-- | :-- |
| Browser UI · HTML/CSS/JavaScript | Python · Go · PostgreSQL · Redis | Git · Docker · Prometheus · Grafana |

## ◈ What keeps me curious

<table>
<tr><td width="33%" valign="top"><b>01 / Explain the change</b><br/>Connect a diff to the code and tests it may affect.</td><td width="33%" valign="top"><b>02 / Expect failure</b><br/>Give retries, recovery and partial results an explicit path.</td><td width="33%" valign="top"><b>03 / Show the evidence</b><br/>Make the system’s decision understandable to the person using it.</td></tr>
</table>

---

## ◈ Contribution trail

<p align="center"><sub>The pixels below are generated from my GitHub contribution graph each day. Purple is the swinging snake; green is the activity grid.</sub></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake.svg" />
  <img src="https://raw.githubusercontent.com/dhairyarvarma/dhairyarvarma/output/github-snake.svg" width="100%" alt="Animated snake moving across Dhairya's contribution history" />
</picture>

<p align="center"><sub>One project at a time. One useful detail at a time.</sub></p>
