---
name: content-strategy
description: "Plan content strategy, content pillars, topic clusters, prioritized topics, editorial calendars, and distribution plans using audience research and business goals. Use when deciding what content to create or improving an existing content roadmap. Excludes standalone article drafting, paid ad copy, and technical SEO audits."
license: MIT
metadata:
  version: "1.0.0"
  upstream-version: "2.1.3"
  source: "https://github.com/coreyhaines31/marketingskills/tree/main/skills/content-strategy"
---

# Content Strategy

Adapted for this personal skill collection from Corey Haines's content-strategy skill. See [ATTRIBUTION.md](ATTRIBUTION.md) and [LICENSE](LICENSE).

## Standalone use and evidence

Use the current project's product and audience context. Match the scope to the request: a topic shortlist does not require a full strategy. Reuse supplied context; ask only for missing details that materially change the recommendations.

Other skills, SEO platforms, CMS integrations, and services mentioned below are optional resources, not bundled dependencies. Use available tools and supplied exports. If live research is unavailable, deliver a provisional plan with assumptions and research gaps rather than implying the research was performed.

Cite the source and date for keyword metrics, competitor observations, customer quotes, and performance claims. Do not invent search volume, ranking difficulty, traffic, conversions, or testimonials. Treat unknown metrics as unknown, and distinguish estimates from measurements. Verify time-sensitive platform capabilities, prices, search results, and industry statistics against current primary sources before relying on them. Upstream benchmarks and channel half-lives are directional examples, not promises or universal facts.

Use scoring weights, calendar ratios, and production counts as adjustable defaults. Fit the plan to the audience's discovery channels, business objective, and production capacity. Make workload and dependencies visible. A content plan or editorial calendar does not itself authorize publishing, outreach, account changes, or recurring automation.

Read [content distribution](references/content-distribution.md) when planning channels and repurposing. Read the [headless CMS guide](references/headless-cms.md) only when CMS selection, content modeling, or editorial infrastructure is relevant; routine strategy work does not require a CMS project.

You are a content strategist. Your goal is to help plan content that drives traffic, builds authority, and generates leads by being either searchable, shareable, or both.

## Before Planning

**Check for product marketing context first:**
If `.agents/product-marketing.md` exists (or `.claude/product-marketing.md`, or the legacy `product-marketing-context.md` filename, in older setups), read it before asking questions. Use that context and only ask for information not already covered or specific to this task.

Gather this context (ask if not provided):

### 1. Business Context
- What does the company do?
- Who is the ideal customer?
- What's the primary goal for content? (traffic, leads, brand awareness, thought leadership)
- What problems does your product solve?

### 2. Customer Research
- What questions do customers ask before buying?
- What objections come up in sales calls?
- What topics appear repeatedly in support tickets?
- What language do customers use to describe their problems?

### 3. Current State
- Do you have existing content? What's working?
- What resources do you have? (writers, budget, time)
- What content formats can you produce? (written, video, audio)

### 4. Competitive Landscape
- Who are your main competitors?
- What content gaps exist in your market?

---

## Treat Content Like a Product

Every piece is its own launch. Content isn't overhead—it's **brand surface area**: each published piece is a new entry point where a stranger can discover you, and hundreds of pieces compound into hundreds of doorways working 24/7. Plan, ship, and promote each piece with the same intent you'd bring to a product release. A post that's written and forgotten has almost no surface area; a post that's distributed (see **Create Once, Distribute Twice** below) multiplies it.

This section covers the searchable/shareable lens, then the execution and prioritization layer: which pieces to make (scoring), how the calendar splits, and per-format discipline.

## Searchable vs Shareable

Classify acquisition content as searchable, shareable, or both. Prioritize the discovery channels that fit the audience and objective; use search as the foundation when evidence supports it. Retention and enablement content may serve a different primary job.

**Searchable content** captures existing demand. Optimized for people actively looking for answers.

**Shareable content** creates demand. Spreads ideas and gets people talking.

### When Writing Searchable Content

**The information-gain gate:** before committing to a searchable piece, read the current top results for its query and write one sentence on what yours will add that none of them have: original data, a real product example, a working tool or template, a clearer answer, a stronger opinion. If you can't write that sentence, don't write the piece. It will be the eleventh copy of the same article, and neither Google nor AI assistants have a reason to prefer it.

- Target a specific keyword or question
- Match search intent exactly—answer what the searcher wants
- Use clear titles that match search queries
- Structure with headings that mirror search patterns
- Place keywords in title, headings, first paragraph, URL
- Provide comprehensive coverage (don't leave questions unanswered)
- Include data, examples, and links to authoritative sources
- Optimize for AI/LLM discovery: clear positioning, structured content, brand consistency across the web

### When Writing Shareable Content

- Lead with a novel insight, original data, or counterintuitive take
- Challenge conventional wisdom with well-reasoned arguments
- Tell stories that make people feel something
- Create content people want to share to look smart or help others
- Connect to current trends or emerging problems
- Share vulnerable, honest experiences others can learn from

---

## Content Types

### Searchable Content Types

**Use-Case Content**
Formula: [persona] + [use-case]. Targets long-tail keywords.
- "Project management for designers"
- "Task tracking for developers"
- "Client collaboration for freelancers"

**Hub and Spoke**
Hub = comprehensive overview. Spokes = related subtopics.
```
/topic (hub)
├── /topic/subtopic-1 (spoke)
├── /topic/subtopic-2 (spoke)
└── /topic/subtopic-3 (spoke)
```
Create hub first, then build spokes. Interlink strategically.

**Note:** Most content works fine under `/blog`. Only use dedicated hub/spoke URL structures for major topics with layered depth (e.g., Atlassian's `/agile` guide). For typical blog posts, `/blog/post-title` is sufficient.

**Template Libraries**
High-intent keywords + product adoption.
- Target searches like "marketing plan template"
- Provide immediate standalone value
- Show how product enhances the template

### Shareable Content Types

**Thought Leadership**
- Articulate concepts everyone feels but hasn't named
- Challenge conventional wisdom with evidence
- Share vulnerable, honest experiences

**Data-Driven Content**
- Product data analysis (anonymized insights)
- Public data analysis (uncover patterns)
- Original research (run experiments, share results)

**Expert Roundups**
15-30 experts answering one specific question. Built-in distribution.

**Case Studies**
Structure: Challenge → Solution → Results → Key learnings

**Meta Content**
Behind-the-scenes transparency. "How We Got Our First $5k MRR," "Why We Chose Debt Over VC."

### Link-Earning Formats

When the goal of a piece is backlinks specifically, format choice matters more than production effort. Foundation Inc.'s B2B Backlink Intelligence Report (March 2026 — a single vendor study of B2B SaaS sites, so treat as directional) measured each format's share of backlinks relative to its share of pages:

| Format | Backlinks vs. page share |
|---|---|
| Statistics / data roundups | **4.25x** |
| Glossary / definition pages | 1.47x |
| Interactive tools / calculators (see **free-tools**) | 1.38x |
| How-to / tutorials | 1.36x |
| Original research / reports | 0.80x |
| Ultimate guides | 0.77x |
| Thought leadership | 0.74x |
| Templates / frameworks | 0.68x |

The counterintuitive read: **curating statistics earns ~5x the links of producing original research.** Writers link to whatever makes citation easiest — a maintained stat-roundup page is citation infrastructure, while original research often gets cited *via* the roundups that aggregate it. Implications: (1) publish a stats page for your category and keep it fresh — it's cheap and compounds, and citable one-line stats are also what LLMs lift, making it an AI-visibility play (see **ai-seo**); (2) when you do run original research, pair it with your own stat-roundup page that presents the findings as citable one-liners, so you capture the links your data generates. The formats at the bottom aren't dead — guides, templates, and thought leadership earn their keep on rankings, conversions, and brand. Judge each piece by the job it's for, and don't expect links from formats that don't earn them.

For programmatic content at scale, see **programmatic-seo** skill.

---

## Content Pillars and Topic Clusters

Content pillars are the 3-5 core topics your brand will own. Each pillar spawns a cluster of related content.

Most of the time, all content can live under `/blog` with good internal linking between related posts. Dedicated pillar pages with custom URL structures (like `/guides/topic`) are only needed when you're building comprehensive resources with multiple layers of depth.

### How to Identify Pillars

1. **Product-led**: What problems does your product solve?
2. **Audience-led**: What does your ICP need to learn?
3. **Search-led**: What topics have volume in your space?
4. **Competitor-led**: What are competitors ranking for?

### Pillar Structure

```
Pillar Topic (Hub)
├── Subtopic Cluster 1
│   ├── Article A
│   ├── Article B
│   └── Article C
├── Subtopic Cluster 2
│   ├── Article D
│   ├── Article E
│   └── Article F
└── Subtopic Cluster 3
    ├── Article G
    ├── Article H
    └── Article I
```

### Pillar Criteria

Good pillars should:
- Align with your product/service
- Match what your audience cares about
- Have search volume and/or social interest
- Be broad enough for many subtopics

---

## Keyword Research by Buyer Stage

Map topics to the buyer's journey using proven keyword modifiers:

### Awareness Stage
Modifiers: "what is," "how to," "guide to," "introduction to"

Example: If customers ask about project management basics:
- "What is Agile Project Management"
- "Guide to Sprint Planning"
- "How to Run a Standup Meeting"

### Consideration Stage
Modifiers: "best," "top," "vs," "alternatives," "comparison"

Example: If customers evaluate multiple tools:
- "Best Project Management Tools for Remote Teams"
- "Asana vs Trello vs Monday"
- "Basecamp Alternatives"

### Decision Stage
Modifiers: "pricing," "reviews," "demo," "trial," "buy"

Example: If pricing comes up in sales calls:
- "Project Management Tool Pricing Comparison"
- "How to Choose the Right Plan"
- "[Product] Reviews"

### Implementation Stage
Modifiers: "templates," "examples," "tutorial," "how to use," "setup"

Example: If support tickets show implementation struggles:
- "Project Template Library"
- "Step-by-Step Setup Tutorial"
- "How to Use [Feature]"

---

## Content Ideation Sources

### 1. Keyword Data

If user provides keyword exports (Ahrefs, SEMrush, GSC), analyze for:
- Topic clusters (group related keywords)
- Buyer stage (awareness/consideration/decision/implementation)
- Search intent (informational, commercial, transactional)
- Quick wins (low competition + decent volume + high relevance)
- Content gaps (keywords competitors rank for that you don't)

Output as prioritized table:
| Keyword | Volume | Difficulty | Buyer Stage | Content Type | Priority |

### 2. Call Transcripts

If user provides sales or customer call transcripts, extract:
- Questions asked → FAQ content or blog posts
- Pain points → problems in their own words
- Objections → content to address proactively
- Language patterns → exact phrases to use (voice of customer)
- Competitor mentions → what they compared you to

Output content ideas with supporting quotes.

### 3. Survey Responses

If user provides survey data, mine for:
- Open-ended responses (topics and language)
- Common themes (30%+ mention = high priority)
- Resource requests (what they wish existed)
- Content preferences (formats they want)

### 4. Forum Research

Use web search to find content ideas:

**Reddit:** `site:reddit.com [topic]`
- Top posts in relevant subreddits
- Questions and frustrations in comments
- Upvoted answers (validates what resonates)

**Quora:** `site:quora.com [topic]`
- Most-followed questions
- Highly upvoted answers

**Other:** Indie Hackers, Hacker News, Product Hunt, industry Slack/Discord

Extract: FAQs, misconceptions, debates, problems being solved, terminology used.

### 5. Competitor Analysis

Use web search to analyze competitor content:

**Find their content:** `site:competitor.com/blog`

**Analyze:**
- Top-performing posts (comments, shares)
- Topics covered repeatedly
- Gaps they haven't covered
- Case studies (customer problems, use cases, results)
- Content structure (pillars, categories, formats)

**Identify opportunities:**
- Topics you can cover better
- Angles they're missing
- Outdated content to improve on

### 6. Sales and Support Input

Extract from customer-facing teams:
- Common objections
- Repeated questions
- Support ticket patterns
- Success stories
- Feature requests and underlying problems

---

## Prioritizing Content Ideas

Score each idea on four factors:

### 1. Customer Impact (40%)
- How frequently did this topic come up in research?
- What percentage of customers face this challenge?
- How emotionally charged was this pain point?
- What's the potential LTV of customers with this need?

### 2. Content-Market Fit (30%)
- Does this align with problems your product solves?
- Can you offer unique insights from customer research?
- Do you have customer stories to support this?
- Will this naturally lead to product interest?

### 3. Search Potential (20%)
- What's the monthly search volume?
- How competitive is this topic?
- Are there related long-tail opportunities?
- Is search interest growing or declining?

### 4. Resource Requirements (10%)
- Do you have expertise to create authoritative content?
- What additional research is needed?
- What assets (graphics, data, examples) will you need?

### Scoring Template

| Idea | Customer Impact (40%) | Content-Market Fit (30%) | Search Potential (20%) | Resources (10%) | Total |
|------|----------------------|-------------------------|----------------------|-----------------|-------|
| Topic A | 8 | 9 | 7 | 6 | 7.9 |
| Topic B | 6 | 7 | 9 | 8 | 7.0 |

Score 1-10 per factor, multiply by the weight, and sum for the total: 0.4 × customer impact + 0.3 × fit + 0.2 × search potential + 0.1 × resource feasibility. A higher resource score means easier production with available people, assets, and expertise. Explain the evidence and uncertainty behind each score. Rank the list, then account for prerequisites and capacity when scheduling.

---

## Calendar Split: 60/30/10

Balance the editorial calendar so search compounds while shareable pieces keep you visible:

- **60% searchable** — the foundation. Demand you can capture predictably (use-case content, hub/spoke, how-tos).
- **30% shareable** — thought leadership, original data, opinion. Creates demand and earns links/mentions.
- **10% experimental** — new formats, channels, or bets. Cheap insurance against a stale mix.

This is a starting ratio, not a rule. A brand-new blog may over-index on searchable to build a base; an established brand chasing category leadership may push shareable higher.

---

## Per-Format Execution Discipline

Treating content like a product means each format has a production standard, not just a topic:

- **Blog post** — write **10 title options** before drafting (the title does most of the work; pick the strongest). Plan **~5 editing passes** (structure, clarity, evidence, line edit, headline/SEO). For the writing itself, see **copywriting**.
- **Long-form guide** — the flagship of a pillar. Comprehensive enough to be *the* resource; structured with a table of contents and internal links to spokes. Build the hub before the spokes.
- **Video** — script the hook first; front-load the payoff. Repurpose into short-form clips at creation time (see **social**).
- **Podcast** — one interview yields a transcript, quote graphics, short clips, and a written recap. Design the episode knowing it will be atomized.
- **Email** — one idea per send; the subject line is the title—write several and pick. For sequences and lifecycle, see **emails**.

---

## Create Once, Distribute Twice

Creating content is half the job—distribution is the other half, and most teams skip it. The philosophy: **one exceptional piece, reformatted and repurposed across every channel, not a fresh piece per platform.** Pouring effort into a single flagship and then distributing it everywhere beats spreading thin effort across many mediocre platform-native posts.

Build **distribution hooks into the piece at creation time**, not after: write subheads that stand alone as social posts, structure sections to be lifted out modularly, and pull quotes/stats you already know you'll graphic-ify. A well-designed guide is a distribution kit in disguise.

**The ORB Framework as a funnel** — route attention from borrowed → rented → owned, which maps to discovery → engagement → conversion:

- **Borrowed** (other people's audiences: podcasts, guest posts, partnerships) — discovery / breakthrough reach.
- **Rented** (social platforms, ad networks) — engagement, but you don't own the audience or the algorithm.
- **Owned** (email list, blog, community) — conversion and the only durable asset. Everything upstream should funnel here.

ORB mechanics live in the **launch** skill (channel-type playbook) and content atomization/repurposing lives in **social**; the value here is consolidating the *distribute* half of content strategy so it has a home.

**Failure modes to avoid:**
- **Spray-and-pray** — posting everywhere with no flagship and no repurposing plan. Effort scatters, nothing compounds.
- **Platform dependency** — building on rented land. Facebook organic reach fell from ~20% to under 2%; any rented channel can throttle you overnight.
- **The ownership paradox** — teams spend ~90% of effort on channels they don't control (rented/borrowed) and neglect the owned assets that actually convert and can't be taken away.

For the full distribution spine—the Content Distribution Flywheel, platform half-lives, and the atomization checklist—see the reference below.

---

## Output Format

When creating a content strategy, provide:

### 1. Content Pillars
- 3-5 pillars with rationale
- Subtopic clusters for each pillar
- How pillars connect to product

### 2. Priority Topics
For each recommended piece:
- Topic/title
- Searchable, shareable, or both
- Content type (use-case, hub/spoke, thought leadership, etc.)
- Target keyword and buyer stage
- Why this topic (customer research backing)

### 3. Topic Cluster Map
Visual or structured representation of how content interconnects.

### 4. Execution and Measurement (when requested)
For a roadmap or editorial calendar, add owner or required role, estimated effort, dependencies, target date or sequence, distribution channels, CTA, and success metric. Use realistic capacity rather than filling every date. Separate supplied facts, research findings, and assumptions. Include a review point for deciding what to refresh, expand, or retire.

---

## Task-Specific Questions

1. What patterns emerge from your last 10 customer conversations?
2. What questions keep coming up in sales calls?
3. Where are competitors' content efforts falling short?
4. What unique insights from customer research aren't being shared elsewhere?
5. Which existing content drives the most conversions, and why?

---

## References

- **[Content Distribution Spine](references/content-distribution.md)**: Create Once Distribute Twice, ORB as a funnel, the ownership paradox, platform half-lives, the Content Distribution Flywheel, and the per-flagship atomization checklist
- **[Headless CMS Guide](references/headless-cms.md)**: CMS selection, content modeling for marketing, editorial workflows, platform comparison (Sanity, Contentful, Strapi)

---

## Related Skills

- **copywriting**: For writing individual content pieces
- **seo-audit**: For technical SEO and on-page optimization
- **ai-seo**: For optimizing content for AI search engines and getting cited by LLMs
- **programmatic-seo**: For scaled content generation
- **site-architecture**: For page hierarchy, navigation design, and URL structure
- **emails**: For email-based content
- **social**: For social media content, content atomization, and repurposing execution
- **launch**: For the ORB channel-type playbook and launch-day distribution
