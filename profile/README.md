# BriarForge AI Team

This organization is supported by a small coordinated AI team with distinct roles.

## Team

_Source of truth for model data: `/Users/mike/.hermes/config.yaml` and `/Users/mike/.hermes/profiles/*/config.yaml`, read live on 2026-05-26._

| Member | Role | Provider | Model version | Config version |
| --- | --- | --- | --- | --- |
| Aoife Brennan / Hermes Prime | Strategic lead — systems thinking, long-term planning, synthesis, prioritization, governance, and coordination | `minimax` | `minimax-m2.7` (primary) | `23` |
| Declan Murphy | Operator — execution, coding, debugging, delivery, verification, and delegated throughput | `openai-codex` | `gpt-5.5` | `23` |
| Milena Petrova | Analyst — research, evidence checks, source quality, comparisons, and decision support | `opencode-go` | `glm-5.1` | `23` |
| Sofia Novak | Designer — UI/UX, visual hierarchy, user flows, interaction quality, and content clarity | `opencode-go` | `mimo-v2-omni` | `null` |


## Fallback Models

| Agent | Primary | Fallback |
| --- | --- | --- |
| Aoife Brennan | `minimax-m2.7` | `opencode-go qwen3.6-plus` |
| Declan Murphy | `gpt-5.5` | `minimax minimax-m2.7` |
| Milena Petrova | `glm-5.1` | `minimax minimax-m2.7` |
| Sofia Novak | `mimo-v2-omni` | `minimax minimax-m2.7` |

## Hermes root

| Scope | Provider | Model version | Backend |
| --- | --- | --- | --- |
| Root default | `openai-codex` | `gpt-5.3-codex` | `https://chatgpt.com/backend-api/codex` |

## Operating pattern

- **Aoife / Hermes Prime** drives strategy, decomposition, review standards, governance, and coordination.
- **Declan** owns execution-heavy workstreams when assigned.
- **Milena** strengthens decisions with research, source checks, and evidence review.
- **Sofia** reviews user-facing experience, visual systems, flows, and copy clarity.
- The team is organized to separate direction from throughput: strategy stays centralized while execution, research, and design review can scale.
