---
name: competitor-deep-dive
description: Report-writing skill for turning detailed, already-collected competitor research materials into a PM-grade competitor deep-dive report. Use when the user provides or references substantial competitor inputs such as research notes, PDFs, demo observations, hands-on testing notes, launch posts, screenshots, interview notes, or market observations and asks for a competitor analysis report, product deep dive, strategic readout, battlecard-style report, product teardown report, or distilled competitor report. Do not use as an action skill for primary research, web browsing, outreach, testing, implementation, or executing recommendations; request more source material if the competitor details are too thin.
---

# Competitor Deep Dive

## Operating Principle

Turn detailed competitor evidence into a strategic product report. Do not merely list features. Explain who the product is for, what job it performs, why it is hard to copy, where it breaks down in real use, and what the true axis of competition is.

This is a report-generation skill. Use supplied research materials as the evidence base. Do not invent primary research, run new tests, browse for fresh data, or execute follow-up actions unless the user separately asks for that work.

## Workflow

1. Define the one-line thesis.
   - Name the product, company, launch context if known, and target user.
   - State the product's strategic claim in one sentence: "The product wins because..."
   - Prefer a concrete product truth over vague praise.

2. Identify the real differentiator.
   - Separate model quality, UI, workflow, distribution, ecosystem, pricing, data, deployment, compliance, and community.
   - Ask which advantage is hardest for competitors to copy.
   - Call out whether the product competes on capability depth, ease of use, speed to value, trust, cost, distribution, or ownership of the full workflow.

3. Map core capabilities.
   - Cluster capabilities by user job, not by menu structure.
   - Include the "last mile" parts competitors often miss: provisioning, deployment, payments, publishing, collaboration, monitoring, support, analytics, and post-launch operations.
   - Note which capabilities are native, integrated through partners, or left to the user.

4. Compare against meaningful alternatives.
   - Pick competitors from adjacent categories, not only direct clones.
   - Use a matrix with dimensions that expose strategic tradeoffs.
   - Recommended dimensions: target user, interface, output, deployment, backend and data, payments or monetization, model stack, codebase depth, version control, collaboration, ecosystem, pricing, and ownership/control.

5. Add hands-on evidence.
   - Include first-person usage notes when available.
   - Capture where the product succeeds, where it fails, and what conditions make it fail.
   - Look for failure modes such as unclear requirement handling, wrong mode selection, weak model routing, unverified fixes, generic design output, brittle integrations, missing export paths, or poor iteration loops.

6. Synthesize the strategic divide.
   - End the comparison with the simple read: "The real divide is not X; it is Y."
   - Explain what the product assumes the user brings versus what it provides for them.
   - Name the product's wedge, moat, and ceiling.

7. Write implications, not an action plan.
   - Give report-level implications for product, positioning, roadmap, GTM, or sales.
   - Separate "must respond now," "monitor," and "ignore" as analytical categories.
   - Tie implications to the competitor's durable advantage and observed weaknesses.

## Output Shape

Use this structure unless the user asks for another format:

1. **Headline Thesis**: One sharp sentence.
2. **Overview**: Launch/context, target user, promise, and why it matters.
3. **What Makes It Unique**: 3-5 bullets focused on hard-to-copy advantages.
4. **Core Capabilities**: Grouped by user job or workflow stage.
5. **Competitor Matrix**: Compare against 2-4 meaningful alternatives.
6. **Hands-On Notes**: Real usage strengths, rough edges, and failure modes.
7. **Strategic Read**: The true basis of competition.
8. **Implications**: Product, positioning, GTM, and watch items. Keep this as report analysis, not an execution plan.

## Comparison Matrix Guidance

Prefer dimensions that reveal assumptions:

| Dimension | Competitor | Alternative 1 | Alternative 2 | Our Product |
| --- | --- | --- | --- | --- |
| Target user | Who it is really built for |  |  |  |
| Interface | How the user expresses intent |  |  |  |
| Output | What the user gets at the end |  |  |  |
| Last mile | What happens after generation |  |  |  |
| Ownership | Who controls repo, hosting, data, payments |  |  |  |
| Moat | Hardest advantage to copy |  |  |  |
| Weakness | Where it predictably breaks |  |  |  |

## Quality Bar

- Use evidence-backed claims. Mark assumptions explicitly.
- Prefer strategic contrast over exhaustive feature inventory.
- Do not confuse polish with moat.
- Do not over-index on the model when distribution, workflow, or ecosystem is the real advantage.
- Include caveats even when the product is impressive.
- Make the conclusion useful for a PM decision: build, partner, position against, monitor, or ignore.
- If the source material is sparse, state what is missing instead of filling gaps with unsupported claims.

