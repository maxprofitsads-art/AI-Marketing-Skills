# Lead Magnets

A reusable skill for choosing, planning, and improving lead magnets that attract qualified prospects. Adapted from [Corey Haines's marketingskills](https://github.com/coreyhaines31/marketingskills/tree/main/skills/lead-magnets).

## Download and install

[Download Lead Magnets ZIP](https://github.com/maxprofitsads-art/AI-Marketing-Skills/raw/refs/heads/main/downloads/lead-magnets.zip) or [browse the skill](https://github.com/maxprofitsads-art/AI-Marketing-Skills/tree/main/skills/lead-magnets).

In Codex, paste:

```text
Use $skill-installer to install the skill from https://github.com/maxprofitsads-art/AI-Marketing-Skills/tree/main/skills/lead-magnets
```

For manual installation, extract the ZIP and copy the entire `lead-magnets` folder to `~/.agents/skills/` (Windows: `%USERPROFILE%\.agents\skills\`). For a single project, use that project's `.agents/skills/` directory. The resulting path should end in `skills/lead-magnets/SKILL.md`, with its supporting folders beside that file. Restart Codex if it does not appear. See the [official skill guidance](https://learn.chatgpt.com/docs/build-skills).

This standalone skill does not require a plugin marketplace listing or paid marketing tools. Producing PDFs, spreadsheets, websites, or email automations requires suitable tools in your environment. Planning does not automatically connect or publish to those services.

## What it helps with

- Selecting a format and topic for the audience's buyer stage.
- Developing a content outline and a natural next step toward the product.
- Planning gating, capture fields, landing pages, and delivery.
- Choosing promotion channels and evaluating qualified-lead outcomes.
- Turning an owned course, podcast, webinar series, or newsletter library into a source-backed agent skill.

## Try it

```text
Use $lead-magnets to recommend three lead magnet ideas and develop the strongest one.
Business: [what we sell]
Audience: [who we want to attract]
Goal: [lead quality, list growth, or product education]
Existing assets: [articles, templates, research, or expertise]
Capacity: [time, budget, and available tools]
```

Other examples:

- `Use $lead-magnets to plan a content upgrade for this blog post.`
- `Use $lead-magnets to improve this offer using our landing-page and lead-quality data.`
- `Use $lead-magnets to plan a source-backed skill from these course materials that we own.`

## Package contents

```text
lead-magnets/
  SKILL.md
  agents/openai.yaml
  references/format-guide.md
  references/benchmarks.md
  references/content-to-skill.md
  references/content-to-skill-corpus-design.md
  references/content-to-skill-release.md
  evals/evals.json
  LICENSE
  ATTRIBUTION.md
  UPSTREAM_COMMIT.txt
  README.md
```

Includes five reference guides and 9 upstream evaluation scenarios. There are no code dependencies for using the instructions. The evaluation scenarios have not been run as a behavioral benchmark for this adaptation. Benchmark ranges and cost estimates are illustrative upstream guidance that needs verification. No client installation test has been performed for this distribution package.

To report a problem, [open an issue](https://github.com/maxprofitsads-art/AI-Marketing-Skills/issues) with the skill name and the relevant example. Do not include private customer information.

Licensed under [MIT](LICENSE). Preserve the [attribution](ATTRIBUTION.md) and license when redistributing.
