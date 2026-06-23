---
name: decision-lens
description: Applies a value-first decision workflow for hard, high-stakes choices using value/cost prioritization and key thinking models. Use when the user needs strategy, prioritization, tradeoff analysis, or asks whether something is worth doing.
---

# Decision Lens

## Quick Start

Use this skill when the user needs high-quality judgment under ambiguity, especially when the decision is hard, high-stakes, or expensive to get wrong.

Default goals:
- find the real problem
- judge whether it is worth doing
- prioritize by value versus cost
- reduce unnecessary complexity
- surface key insight and future implications
- recommend a path, not just list options

This skill should feel like snow in winter, not icing on cake:
- most useful when stakes are real
- most useful when simple execution is not the bottleneck
- least useful when the task is already obvious and low-risk

Its best output is leverage:
- find the move that creates outsized change
- remove bottlenecks, exploit asymmetry, or improve option value

For the full framework and model table, see [references/decision-framework.md](references/decision-framework.md).

## Workflow

1. Identify the real decision.
2. Run a value gate:
   - What problem actually matters?
   - Is this worth doing now?
   - What is the highest-leverage slice?
3. Reduce entropy:
   - remove low-value complexity
   - compress options into a small decision set
   - ask only questions that would materially change the recommendation
4. Place options in the value/cost quadrant:
   - high value / low cost: do now
   - high value / high cost: stage it
   - low value / low cost: only if it helps something else
   - low value / high cost: do not recommend by default
5. Calibrate with 3-5 models as needed:
   - first principles for fake constraints
   - systems thinking for multi-party or feedback-loop problems
   - second-order thinking for downstream consequences
   - inversion for failure modes
   - Bayesian thinking for updating beliefs from new evidence
   - incentives, opportunity cost, margin of safety, and via negativa when relevant
6. For strategic decisions, add one short pass:
   - insight: what important truth, hidden constraint, or misread signal matters most?
   - foresight: if this path continues, what becomes true later?
   - leverage: what smallest move creates the biggest shift?
7. Recommend one path and explain why.

## Model Routing

- Vague constraints or inherited assumptions: use first principles.
- Cross-functional or ecosystem problems: use systems thinking.
- Short-term upside with unclear long-term impact: use second-order thinking.
- High downside or irreversibility: use inversion and margin of safety.
- Evolving evidence: use base rates and Bayesian updates.
- People-dependent outcomes: use incentives.
- Overloaded scope: use opportunity cost and via negativa.
- Need the hidden variable: add an insight pass.
- Need the future shape of consequences: add a foresight pass.
- Need a small move with outsized impact: add a leverage pass.

## Output Rules

- Lead with the recommendation.
- For meaningful decisions, include a "do nothing" option.
- Distinguish facts, assumptions, priors, and updated beliefs.
- Expand depth only when complexity or stakes justify it.
- If a request is low-value and high-cost, say so clearly.
- Use insight and foresight only when they materially improve the recommendation.
- Prefer leverage over volume: smaller move, larger effect.

## Output Shape

For simple tasks:
- `结论`
- `为什么`
- `下一步`

For complex tasks:
- `意图推断`
- `关键洞察`
- `杠杆点`
- `角色地图`
- `方案对比`
- `模型校准`
- `未来推演`
- `执行路径`
- `反脆弱设计`
- `决策建议`
