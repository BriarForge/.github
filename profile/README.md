# BriarForge AI Team

This organisation is supported by a small coordinated AI team with distinct roles.

## Team

_Source of truth for model data: `/Users/mike/.hermes/config.yaml` and `/Users/mike/.hermes/profiles/*/config.yaml`, read live on 2026-07-12._

| Member | Role | Provider | Model version | Config version |
| --- | --- | --- | --- | --- |
| Aoife Brennan / Hermes Prime | Strategic lead — systems thinking, long-term planning, synthesis, prioritization, governance, and coordination | `moa` | `moa/m3->grok-4.5` | `23` |
| Declan Murphy | Operator — execution, coding, debugging, delivery, verification, and delegated throughput | `minimax` | `minimax/MiniMax-M2.7` | `23` |
| Milena Petrova | Analyst — research, evidence checks, source quality, comparisons, and decision support | `opencode-go` | `opencode-go/glm-5.1` | `23` |
| Sofia Novak | Designer — UI/UX, visual hierarchy, user flows, interaction quality, and content clarity | `minimax` | `minimax/MiniMax-M2.7` | `null` |


## Fallback Models

| Agent | Primary | Fallback |
| --- | --- | --- |
| Aoife Brennan | `moa/m3->grok-4.5` | MOA — ref `xai-oauth/grok-4.5`, aggregator `minimax/minimax-m3` |
| Declan Murphy | `minimax/MiniMax-M2.7` | — |
| Milena Petrova | `opencode-go/glm-5.1` | `minimax/MiniMax-M2.7` |
| Sofia Novak | `minimax/MiniMax-M2.7` | — |

## Hermes root

| Scope | Provider | Model version | Backend |
| --- | --- | --- | --- |
| Root default | `minimax` | `minimax/minimax-m2.7` | Hermes default CLI |

## Operating pattern

- **Aoife / Hermes Prime** drives strategy, decomposition, review standards, governance, and coordination.
- **Declan** owns execution-heavy workstreams when assigned.
- **Milena** strengthens decisions with research, source checks, and evidence review.
- **Sofia** reviews user-facing experience, visual systems, flows, and copy clarity.
- The team is organised to separate direction from throughput: strategy stays centralised while execution, research, and design review can scale.
