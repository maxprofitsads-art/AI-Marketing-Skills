# Content Strategy

A reusable skill for deciding what content to create, prioritizing topics, and planning how to distribute and measure it. Adapted from [Corey Haines's marketingskills](https://github.com/coreyhaines31/marketingskills/tree/main/skills/content-strategy).

## Download and install

[Download Content Strategy ZIP](https://github.com/maxprofitsads-art/AI-Marketing-Skills/raw/refs/heads/main/downloads/content-strategy.zip) or [browse the complete skill](https://github.com/maxprofitsads-art/AI-Marketing-Skills/tree/main/skills/content-strategy).

In Codex, paste:

```text
Use $skill-installer to install the skill from https://github.com/maxprofitsads-art/AI-Marketing-Skills/tree/main/skills/content-strategy
```

For manual installation, extract the ZIP and copy the whole `content-strategy` folder to `~/.agents/skills/` (Windows: `%USERPROFILE%\.agents\skills\`). For a single project, use its `.agents/skills/` directory. The final path should end in `skills/content-strategy/SKILL.md`, with the supporting folders beside that file. Restart Codex if the skill does not appear. See the [official skill guidance](https://learn.chatgpt.com/docs/build-skills).

This is a standalone skill folder. No paid SEO tool, advertising connection, or plugin marketplace listing is required. Live research and CMS work depend on available tools; supplied context and exports are enough to start planning.

## What it does

- Defines content pillars and topic clusters around audience needs and product fit.
- Maps topics to buyer stages and search or sharing intent.
- Prioritizes ideas using customer impact, fit, search potential, and production feasibility.
- Plans editorial work, distribution, repurposing, and measurement.
- Supports CMS selection and content modeling when those are part of the task.

## Try it

```text
Use $content-strategy to create a 90-day content roadmap.
Business: [what we sell]
Audience: [who we serve]
Goal: [leads, traffic, authority, or retention]
Capacity: [people, hours, budget, and formats]
Evidence: [customer questions, keyword data, existing content, or analytics]
```

Other requests:

- `Use $content-strategy to turn these customer questions into three content pillars and a prioritized topic list.`
- `Use $content-strategy to prioritize this keyword export by product fit and buyer stage.`
- `Use $content-strategy to plan distribution and repurposing for this flagship guide.`

## Package contents

```text
content-strategy/
  SKILL.md
  agents/openai.yaml
  references/content-distribution.md
  references/headless-cms.md
  evals/evals.json
  LICENSE
  ATTRIBUTION.md
  UPSTREAM_COMMIT.txt
  README.md
```

The reference guides are loaded only when relevant. Industry benchmarks, platform features, and prices are upstream guidance that should be verified before use. Missing metrics should remain unknown rather than being invented. The evaluation file contains upstream example scenarios, not a completed behavioral benchmark for this adaptation.

Licensed under [MIT](LICENSE). Preserve the license and [source attribution](ATTRIBUTION.md) when redistributing.
