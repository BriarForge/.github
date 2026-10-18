# BriarForge AI Team

This organisation is supported by a small coordinated AI team with distinct roles.

## Team

_Source of truth for model data: `/home/mike/.hermes/config.yaml` and `/home/mike/.hermes/profiles/*/config.yaml`, read live on 2026-10-18._

| Member | Role | Provider | Model version | Config version |
| --- | --- | --- | --- | --- |
| Aoife Brennan / Hermes Prime | Strategic lead — systems thinking, long-term planning, synthesis, prioritization, governance, and coordination | `openai-codex` | `openai-codex/gpt-6-sol` | `49` |
| Declan Murphy | Operator — execution, coding, debugging, delivery, verification, and delegated throughput | `moa` | `moa/m3->grok-4.6` | `49` |
| Milena Petrova | Analyst — research, evidence checks, source quality, comparisons, and decision support | `moa` | `moa/grok-4.6->m3` | `49` |
| Sofia Novak | Designer — UI/UX, visual hierarchy, user flows, interaction quality, and content clarity | `moa` | `moa/grok-4.6->m3` | `49` |


## Fallback Models

| Agent | Primary | Fallback |
| --- | --- | --- |
| Aoife Brennan | `openai-codex/gpt-6-sol` | `xai-oauth/grok-4.6`, `minimax/minimax-m3` |
| Declan Murphy | `moa/m3->grok-4.6` | `xai-oauth/grok-4.6`, `minimax/minimax-m3` |
| Milena Petrova | `moa/grok-4.6->m3` | `xai-oauth/grok-4.6`, `minimax/minimax-m3` |
| Sofia Novak | `moa/grok-4.6->m3` | `xai-oauth/grok-4.6`, `minimax/minimax-m3` |

_MOA identifiers are presets, not individual models. The fallback column lists the configured `fallback_providers` in order._

## Hermes root

| Scope | Provider | Model version | Backend |
| --- | --- | --- | --- |
| Root default | `openai-codex` | `openai-codex/gpt-6-sol` | Hermes default CLI (config v49) |

## Operating pattern

- **Aoife / Hermes Prime** drives strategy, decomposition, review standards, governance, and coordination.
- **Declan** owns execution-heavy workstreams when assigned.
- **Milena** strengthens decisions with research, source checks, and evidence review.
- **Sofia** reviews user-facing experience, visual systems, flows, and copy clarity.
- The team is organised to separate direction from throughput: strategy stays centralised while execution, research, and design review can scale.
