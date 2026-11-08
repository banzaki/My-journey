# Bruno — Software Projects & Engineering Portfolio

I build practical web applications, AI-powered experiences, and automation tools. My focus is turning a defined problem into working software with clear architecture, useful documentation, and deployable results.

**GitHub:** [@banzaki](https://github.com/banzaki) · **Location:** Brazil

## Featured public project

### [Stoic Oracle](https://github.com/banzaki/stoic-oracle) — AI conversations grounded in original texts

[![Stoic Oracle CI](https://github.com/banzaki/stoic-oracle/actions/workflows/ci.yml/badge.svg)](https://github.com/banzaki/stoic-oracle/actions/workflows/ci.yml)

[Try the live application](https://stoic-oracle-eosin.vercel.app)

An interactive experience with portrayals of Marcus Aurelius, Seneca, and Epictetus. It combines text retrieval, source-linked responses, quotation verification, and multiple AI personas.

**Technology:** Next.js, React, TypeScript, Tailwind CSS, Anthropic API, Redis, Vercel.

**Engineering highlights (documented in the repository):**
- Hybrid retrieval pipeline using BM25 and semantic re-ranking.
- Source references and explicit distinctions between verified quotations, paraphrases, and AI-generated interpretation.
- Server-side API credentials, per-visitor limits, and an atomic Redis-based spending guard.
- Regression evaluation scripts and operational controls for model usage.

[Explore architecture and setup](https://github.com/banzaki/stoic-oracle#how-it-works)

## Other engineering work

These repositories are currently private; the summaries describe areas of work rather than public code you can inspect.

| Project | Focus | Engineering topics |
| --- | --- | --- |
| WARZIL ([live game](https://warzil.com.br)) | Multiplayer strategy game | React, Cloudflare Workers, Durable Objects, authoritative game state, simulated AI matches |
| Job Sniper | Opportunity discovery and alerts | Node.js, SQLite, source adapters, deduplication, retries, Telegram notifications |
| SMM Control Center | Local project portfolio management | Native Node.js, state transitions, persistence, validation and automated tests |

## Demonstrations and code

- **[Stoic Oracle — live](https://stoic-oracle-eosin.vercel.app):** a public, inspectable codebase with technical documentation and CI.
- **[WARZIL — live](https://warzil.com.br):** a playable deployment; its source repository remains private while the Git history and operational assets are reviewed for safe publication.
- **Job Sniper:** backend automation case study prepared internally; source and operational documentation are private pending review.

## How I approach development

I value clear requirements, explicit tradeoffs, and repeatable verification. My projects incorporate AI-assisted development workflows, and I aim to make the architecture, operational limits, and implementation decisions understandable and reviewable rather than treating generated code as a black box.

## For recruiters and collaborators

Start with [Stoic Oracle](https://github.com/banzaki/stoic-oracle): there is a live demo, setup guidance, an explanation of the retrieval/verification pipeline, and documented operational safeguards.

**Portfolio note:** Private projects are not presented as publicly reviewable. More case studies and source code can be published after a privacy/security review.
