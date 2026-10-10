# Ad Creative

A reusable personal skill for writing and improving paid ad creative, adapted from [Corey Haines's marketingskills](https://github.com/coreyhaines31/marketingskills/tree/main/skills/ad-creative).

## Included files

```text
ad-creative/
  SKILL.md                         Skill instructions and workflow
  agents/openai.yaml               Codex display metadata and starter prompt
  references/                     11 guides for copy, formats, and production
  assets/creative-review-template.html
                                  Editable stakeholder review page
  evals/evals.json                 Upstream example evaluation scenarios
  LICENSE                         Original MIT license
  ATTRIBUTION.md                    Source version and adaptation details
  UPSTREAM_COMMIT.txt               Exact source revision
  README.md                        Usage and GitHub packaging notes
```

The skill supports fresh ad copy, performance-based iterations, grounded static batches, and creative strategy. References cover hooks, awareness-based headlines, platform specifications, static templates, creative roadmaps, review pages, and several video formats.

## Download and install

[Download Ad Creative ZIP](https://github.com/maxprofitsads-art/AI-Marketing-Skills/raw/refs/heads/main/downloads/ad-creative.zip) or [browse the complete skill](https://github.com/maxprofitsads-art/AI-Marketing-Skills/tree/main/skills/ad-creative).

In Codex, ask:

```text
Use $skill-installer to install the skill from https://github.com/maxprofitsads-art/AI-Marketing-Skills/tree/main/skills/ad-creative
```

For manual installation, extract the ZIP and copy the entire `ad-creative` folder into `~/.agents/skills/` (Windows: `%USERPROFILE%\.agents\skills\`). For project-only use, copy it into `.agents/skills/` in the project. The final path must be `ad-creative/SKILL.md` inside that skills directory, with its supporting folders beside it. If the skill does not appear, restart Codex. See the [official skill installation guidance](https://learn.chatgpt.com/docs/build-skills).

This is a standalone skill folder; it does not require a plugin marketplace listing. Installing it does not install paid media services or connect advertising accounts. To redistribute your own adaptation, preserve `LICENSE`, `ATTRIBUTION.md`, and the supporting folders.

## Use the skill

Example requests:

- `Use $ad-creative to draft Google search headlines and descriptions for this offer.`
- `Use $ad-creative to analyze this performance export and write variations of the strongest concepts.`
- `Use $ad-creative to create static ad concepts grounded in these customer reviews.`
- `Use $ad-creative to prepare a stakeholder review page for these concepts.`

Supply your product, audience, offer, platform, and any brand requirements. Provide real reviews, claims evidence, and performance data when relevant. The skill can work from pasted information or files; it does not require the author's other skills or paid tools. Actual image/video production depends on tools available in your environment.

Reference specifications, tool prices, and format rankings need current verification before use. The HTML file is a reusable template with example content, not a completed campaign. The evaluation JSON contains upstream prompts and expectations; some assume the original author's full skill suite. Adapt those expectations for this standalone package before using them as a test harness.

Licensed under [MIT](LICENSE). See [ATTRIBUTION.md](ATTRIBUTION.md) for provenance and local modifications.
