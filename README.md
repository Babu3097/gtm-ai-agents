# GTM AI Agents

**Directing a library of AI marketing agents for a live UK direct-to-consumer e-commerce brand** — built on Claude Code, governed by business context I author.

![Built with](https://img.shields.io/badge/built%20with-Claude%20Code-0d8f8b?style=flat-square) ![Status](https://img.shields.io/badge/status-active-0d8f8b?style=flat-square)

Each agent is a Claude Code skill I select for the task at hand — ad creative, SEO, pricing, customer research. None of them know anything about the brand on their own; the judgement is mine, encoded in a business-context file, and every output is reviewed before it ships as a real ad or page.

> **Note:** the company name and live figures (pricing, discount codes) are withheld from this public repo. The methodology below is real; the business specifics are not.

## Skills demonstrated

| Competency | Where it shows up |
|---|---|
| Requirements analysis | A business-context file defining ICP, positioning and offer structure that the agents execute against |
| Program ownership | Selecting and sequencing which agent runs for which GTM task |
| Quality assurance | Reviewing every AI draft against brand voice and offers before it ships |
| Data-driven iteration | See Results below |

## Results

| Metric | Value |
|---|---|
| Ad-copy turnaround | _add real number — e.g. time per campaign, before vs. after_ |
| Campaigns / assets shipped | _add real number — e.g. count of ads, pages, or emails produced_ |
| Business outcome | _add real number — e.g. conversion, margin, or traffic delta_ |

## My contribution

- **Business context authoring** — positioning, ICP, offer structure and brand voice: the domain knowledge no agent has until it's written down.
- **Agent selection & sequencing** — choosing which skill runs for which task (e.g. `ad-creative` for a paid social launch, `seo-audit` before a site change), and in what order.
- **Quality review** — every AI draft is checked against the brand's actual voice and offers before anything is published or spent against.

## How a task runs

1. **Input** — I supply business context and the task.
2. **Agent runs** — the skill drafts copy, an audit, or a plan.
3. **My review** — edit, reject, or approve the draft.
4. **Ships** — goes live as a real ad, page, or email.

## Agent stack in use

| Agent | Used for |
|---|---|
| `ad-creative` | Paid social ad copy variations, tested against the brand's actual offers |
| `seo-audit` | Technical & on-page health checks on the storefront |
| `pricing` | Reviewing bundle & discount structure against margin |
| `customer-research` | Mining reviews for language real customers use |

## Tech stack

Claude Code · Agent Skills · Markdown business context · Shopify · Meta Ads
