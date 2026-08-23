<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="assets/hero-light.svg">
    <img src="assets/hero-dark.svg" alt="" width="100%">
  </picture>
</div>

<h1 align="center">Rahul</sub></h1>

<p align="center">
  <b>Solo founder, Tokyo.</b><br>
  I build self-hosted software for people who would rather own their data than rent it.
</p>

<p align="center">
  <code>no framework</code> &nbsp; <code>no package manager</code> &nbsp; <code>no bundler</code> &nbsp; <code>zero runtime dependencies</code>
</p>

<br>

## Stratabase

A work-life operating system you host yourself. Documents, projects, planning, time, money, and the graph that ties them together, in one SQLite file that never leaves your machine.

The server is the Python standard library. The browser code is hand-written JavaScript. There is no framework, no package manager and no bundler, and a build gate fails the whole thing if a dependency ever appears.

|  |  |  |
|---|---|---|
| **1,337** commits | **78,378** lines of product code | **325** automated gates |
| **62** active days | **20,615** lines of design system | **241** test suites |
| since 2 June 2026 | **26,390** lines of audit tooling | **0** runtime dependencies |

**Ten modules.** Documents and a block editor, the work board, daily planning, projects and issues, self-defined life trackers, where the hours went, pages as a link map, a command palette. Two more in design: your own model over your own data, and focus sessions.

Two things I would rather be judged on than the feature list. A durability stack built after actually losing work: every document mirrored to plain markdown as you type, verified database snapshots addressed by workspace UUID rather than by path so a moved workspace keeps its history, and an append-only operation log that replays itself and diffs against the live database to prove nothing drifted. And a write path that was silently losing updates, measured at 111 of 320 revision increments dropped under concurrent load, now fixed and pinned by a test that fails on the old code.

## TiME and SEiKO

Two mobile products, native on both platforms. Kotlin and Jetpack Compose on Android, SwiftUI on iOS, a Ruby backend, Python for the assist features.

## Research

LLM inference, quantization, retrieval-augmented generation, and Japanese natural language processing. Published work under [ORCID 0009-0004-7132-3883](https://orcid.org/0009-0004-7132-3883).

## How I work

```
schedule
  weekday  06:00-07:30 JST   morning block, planning and design
  weekday  20:00-22:00 JST   evening block, coding
  weekend  6-10h flexible    deep work, parallel learning
  hard stop 22:00 JST        every day, no exceptions

cadence
  daily      one ticket moves at least one column
  weekly     Sunday evening, five-line log
  monthly    metric thread
  quarterly  retrospective and doctrine update

discipline
  one platform at a time
  one entry point
  one market
  one voice
  AI maximalist
```

Native English, JLPT N1, comfortable in Japanese in more or less any situation a native speaker would be in. MBA in progress alongside the rest of it. Twelve million walking steps, same discipline, different ledger.

<br>

<div align="center">
  <a href="https://rahuls.vercel.app"><b>rahuls.vercel.app</b></a>
  &nbsp;·&nbsp;
  <a href="mailto:watarikai@outlook.com">watarikai@outlook.com</a>
  &nbsp;·&nbsp;
  <a href="https://orcid.org/0009-0004-7132-3883">ORCID</a>
</div>
