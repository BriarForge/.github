# BriarForge AI Team

This organisation is supported by a small coordinated AI team with distinct roles.

## Team

_Source of truth for model data: `/home/mike/.hermes/config.yaml` and `/home/mike/.hermes/profiles/*/config.yaml`, read live on 2026-11-15._

| Member | Role | Provider | Model version | Config version |
| --- | --- | --- | --- | --- |
| Aoife Brennan / Hermes Prime | Strategic lead — systems thinking, long-term planning, synthesis, prioritization, governance, and coordination | `xai-oauth` | `xai-oauth/grok-4.7` | `53` |
| Declan Murphy | Operator — execution, coding, debugging, delivery, verification, and delegated throughput | `xai-oauth` | `xai-oauth/grok-4.7` | `53` |
| Milena Petrova | Analyst — research, evidence checks, source quality, comparisons, and decision support | `claude-subscription-directsdk-experimental` | `claude-subscription-directsdk-experimental/claude-haiku-5-5` | `53` |
| Sofia Novak | Designer — UI/UX, visual hierarchy, user flows, interaction quality, and content clarity | `claude-subscription-directsdk-experimental` | `claude-subscription-directsdk-experimental/claude-haiku-5-5` | `53` |


## Fallback Models

| Agent | Primary | Fallback |
| --- | --- | --- |
| Aoife Brennan | `xai-oauth/grok-4.7` | `minimax/minimax-m3` |
| Declan Murphy | `xai-oauth/grok-4.7` | `minimax/minimax-m3` |
| Milena Petrova | `claude-subscription-directsdk-experimental/claude-haiku-5-5` | `minimax/minimax-m3`, `xai-oauth/grok-4.7` |
| Sofia Novak | `claude-subscription-directsdk-experimental/claude-haiku-5-5` | `minimax/minimax-m3`, `xai-oauth/grok-4.7` |

_The fallback column lists the configured `fallback_providers` in order._

## Hermes root

| Scope | Provider | Model version | Backend |
| --- | --- | --- | --- |
| Root default | `xai-oauth` | `xai-oauth/grok-4.7` | Hermes default CLI (config v53) |

## Operating pattern

- **Aoife / Hermes Prime** drives strategy, decomposition, review standards, governance, and coordination.
- **Declan** owns execution-heavy workstreams when assigned.
- **Milena** strengthens decisions with research, source checks, and evidence review.
- **Sofia** reviews user-facing experience, visual systems, flows, and copy clarity.
- The team is organised to separate direction from throughput: strategy stays centralised while execution, research, and design review can scale.
