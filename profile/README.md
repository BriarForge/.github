# BriarForge AI Team

This organisation is supported by a small coordinated AI team with distinct roles.

## Team

_Source of truth for model data: `/Users/mike/.hermes/config.yaml` and `/Users/mike/.hermes/profiles/*/config.yaml`, read live on 2026-08-30._

| Member | Role | Provider | Model version | Config version |
| --- | --- | --- | --- | --- |
| Aoife Brennan / Hermes Prime | Strategic lead — systems thinking, long-term planning, synthesis, prioritization, governance, and coordination | `moa` | `moa/grok-4.6->m3` | `23` |
| Declan Murphy | Operator — execution, coding, debugging, delivery, verification, and delegated throughput | `moa` | `moa/m3->grok-4.6` | `23` |
| Milena Petrova | Analyst — research, evidence checks, source quality, comparisons, and decision support | `minimax` | `minimax/MiniMax-M3` | `23` |
| Sofia Novak | Designer — UI/UX, visual hierarchy, user flows, interaction quality, and content clarity | `minimax` | `minimax/MiniMax-M3` | `33` |


## Fallback Models

| Agent | Primary | Fallback |
| --- | --- | --- |
| Aoife Brennan | `moa/grok-4.6->m3` | MOA — ref `xai-oauth/grok-4.6`, aggregator `minimax/minimax-m3` |
| Declan Murphy | `moa/m3->grok-4.6` | MOA — ref `minimax/minimax-m3`, aggregator `xai-oauth/grok-4.6` |
| Milena Petrova | `minimax/MiniMax-M3` | — |
| Sofia Novak | `minimax/MiniMax-M3` | — |

## Hermes root

| Scope | Provider | Model version | Backend |
| --- | --- | --- | --- |
| Root default | `minimax` | `minimax/minimax-m3` | Hermes default CLI |

## Operating pattern

- **Aoife / Hermes Prime** drives strategy, decomposition, review standards, governance, and coordination.
- **Declan** owns execution-heavy workstreams when assigned.
- **Milena** strengthens decisions with research, source checks, and evidence review.
- **Sofia** reviews user-facing experience, visual systems, flows, and copy clarity.
- The team is organised to separate direction from throughput: strategy stays centralised while execution, research, and design review can scale.
