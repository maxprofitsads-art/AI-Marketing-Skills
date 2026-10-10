# AI Marketing Skills

Reusable AI skills for marketing work, maintained by [maxprofitsads-art](https://github.com/maxprofitsads-art).

## Available skills

| Skill | What it helps with | Download |
| --- | --- | --- |
| [Ad Creative](skills/ad-creative/README.md) | Paid ad copy, creative concepts, performance-based iterations, video briefs, and stakeholder review pages | [Ad Creative ZIP](https://github.com/maxprofitsads-art/AI-Marketing-Skills/raw/refs/heads/main/downloads/ad-creative.zip) |
| [Content Strategy](skills/content-strategy/README.md) | Content pillars, topic clusters, editorial roadmaps, and distribution plans | [Content Strategy ZIP](https://github.com/maxprofitsads-art/AI-Marketing-Skills/raw/refs/heads/main/downloads/content-strategy.zip) |
| [Lead Magnets](skills/lead-magnets/README.md) | Lead magnet formats, content outlines, gating, delivery, promotion, and source-library skills | [Lead Magnets ZIP](https://github.com/maxprofitsads-art/AI-Marketing-Skills/raw/refs/heads/main/downloads/lead-magnets.zip) |

## Install Ad Creative

In Codex, paste this request:

```text
Use $skill-installer to install the skill from https://github.com/maxprofitsads-art/AI-Marketing-Skills/tree/main/skills/ad-creative
```

Or install manually:

1. [Download the Ad Creative ZIP](https://github.com/maxprofitsads-art/AI-Marketing-Skills/raw/refs/heads/main/downloads/ad-creative.zip) and extract it.
2. Copy the entire `ad-creative` folder to `~/.agents/skills/` (Windows: `%USERPROFILE%\.agents\skills\`). For a single project, use that project's `.agents/skills/` directory.
3. Confirm the resulting path is `.../skills/ad-creative/SKILL.md`, with `references`, `assets`, and `agents` inside the same `ad-creative` folder.
4. If Codex does not show the skill, restart it.

These instructions follow the [official Codex skill guidance](https://learn.chatgpt.com/docs/build-skills). This repository distributes a standalone skill, not a plugin marketplace listing. Other agents that support `SKILL.md` can use the folder with their own installation procedures.

## Install Content Strategy

In Codex, paste:

```text
Use $skill-installer to install the skill from https://github.com/maxprofitsads-art/AI-Marketing-Skills/tree/main/skills/content-strategy
```

For manual installation, [download Content Strategy](https://github.com/maxprofitsads-art/AI-Marketing-Skills/raw/refs/heads/main/downloads/content-strategy.zip), extract it, and copy the whole `content-strategy` folder into the same skills directory described above. See its [README](skills/content-strategy/README.md) for details and examples.

## Install Lead Magnets

In Codex, paste:

```text
Use $skill-installer to install the skill from https://github.com/maxprofitsads-art/AI-Marketing-Skills/tree/main/skills/lead-magnets
```

For manual installation, [download Lead Magnets](https://github.com/maxprofitsads-art/AI-Marketing-Skills/raw/refs/heads/main/downloads/lead-magnets.zip), extract it, and copy the entire `lead-magnets` folder into your skills directory. See its [README](skills/lead-magnets/README.md) for details.

## Try it

```text
Use $ad-creative to write 10 Meta ad variations for my offer.
Product: [what you sell]
Audience: [who it is for]
Offer: [what people get]
Objective: [leads, purchases, or another outcome]
Brand voice: [tone and constraints]
Evidence: [verified product facts, reviews, or results]
```

You can also supply a performance export to improve existing creative, ask for static concepts based on customer reviews, or request a stakeholder review page.

Try Content Strategy with:

```text
Use $content-strategy to create a 90-day content roadmap for my business.
Audience: [who we serve]
Goal: [what content should achieve]
Capacity: [people, hours, and available formats]
Evidence: [customer questions, keyword data, and existing content]
```

Try Lead Magnets with:

```text
Use $lead-magnets to recommend a lead magnet for my ideal customer.
Business: [what we sell]
Audience: [who we want to attract]
Goal: [list growth, qualified leads, or product education]
Existing assets: [content, templates, or expertise]
Capacity: [time, budget, and available tools]
```

## What's included

- Complete skill instructions and Codex display metadata.
- Ad Creative: eleven reference guides, a review-page template, and twenty upstream evaluation scenarios.
- Content Strategy: two reference guides and eight upstream evaluation scenarios.
- Lead Magnets: five reference guides and nine upstream evaluation scenarios.
- MIT license, source attribution, and the exact upstream revision.

No additional code dependencies are required to read and use the skill's instructions. Generating actual images or videos requires suitable tools in your agent environment. Platform specifications and pricing should be checked before production. The sample evaluations are included as examples; they have not been run as a behavioral benchmark for this adaptation.

## Credits and licensing

Ad Creative is adapted from [Corey Haines's marketingskills](https://github.com/coreyhaines31/marketingskills/tree/main/skills/ad-creative). Its [MIT license](skills/ad-creative/LICENSE), original copyright notice, and [adaptation details](skills/ad-creative/ATTRIBUTION.md) are included. Licensing applies to the corresponding skill files; other repository content retains its own licensing.

Content Strategy is also adapted from [Corey Haines's marketingskills](https://github.com/coreyhaines31/marketingskills/tree/main/skills/content-strategy), with its own [MIT license](skills/content-strategy/LICENSE) and [adaptation details](skills/content-strategy/ATTRIBUTION.md).

Lead Magnets is adapted from [Corey Haines's marketingskills](https://github.com/coreyhaines31/marketingskills/tree/main/skills/lead-magnets), with its own [MIT license](skills/lead-magnets/LICENSE) and [adaptation details](skills/lead-magnets/ATTRIBUTION.md).
