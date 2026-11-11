# UX Agent Skills

Five agent skills that turn 19 UX laws into practical instructions for reviewing and improving interfaces.

Each skill is a standalone `SKILL.md` with a description, working approach, law-specific guidance, verification steps, and reporting instructions.

## Skills

| Skill | Laws covered |
| --- | --- |
| [Visual Perception & Grouping](ux-visual-perception/SKILL.md) | Common Region, Prägnanz, Proximity, Similarity, Uniform Connectedness |
| [Attention & Memory](ux-attention-memory/SKILL.md) | Miller’s Law, Serial Position Effect, Von Restorff Effect, Zeigarnik Effect |
| [Speed & Decision-Making](ux-speed-decisions/SKILL.md) | Doherty Threshold, Fitts’ Law, Hick’s Law |
| [Familiarity & Perceived Usability](ux-familiarity-usability/SKILL.md) | Aesthetic Usability Effect, Jakob’s Law |
| [Complexity & Effort](ux-complexity-effort/SKILL.md) | Occam’s Razor, Pareto Principle, Parkinson’s Law, Postel’s Law, Tesler’s Law |

## Use

For an agent that supports skills, add the relevant skill folder to its configured skills directory. Otherwise, supply the relevant `SKILL.md` as instructions alongside the screen, flow, design, or implementation to review.

Example requests:

- Use `$ux-visual-perception` to review the grouping and hierarchy of this dashboard.
- Use `$ux-attention-memory` to find unnecessary memory demands in this checkout flow.
- Use `$ux-speed-decisions` to review feedback timing, target sizes, and choice effort.
- Use `$ux-familiarity-usability` to check conventions and perceived usability in this onboarding flow.
- Use `$ux-complexity-effort` to simplify this workflow while preserving its requirements.

## Approach

The skills distinguish established mathematical models from conceptual principles. They ask agents to support findings with evidence, preserve task requirements, and separate observed results from expected benefits.

Each skill includes reference links for the laws it applies.
