# TARGET: today's build

- **Thing:** Cascade Effect, a one-page interactive simulator where visitors adjust monetary and fiscal policy levers to trace estimated effects from macro policy through markets and sectors to a household’s finances.
- **Audience:** An everyday homeowner or investor who wants a plain-English way to understand how policy changes could affect their borrowing, savings, investments, and purchasing power.
- **Requirements:** One working primary interaction: changing any macro control instantly recalculates the yield curve, market indicators, sector heatmap, household outputs, and three-step Cascade Storyteller; users can adjust a household profile and see estimated monthly cash-flow and portfolio effects; honor my approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label all modeled prices, forecasts, and metrics as illustrative estimates. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** A visually striking dark, layered cascade dashboard: glowing policy controls at the top, animated flows through market and sector cards, and a prominent personal-impact panel at the bottom. Prioritize clear directional cause-and-effect over financial precision.
- **Test:** I can change a policy lever, observe downstream updates across all four levels, verify a yield-curve inversion/steepening boundary, enter a household profile, and identify the standing rule’s effect in the actual preview. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
