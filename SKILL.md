---
name: seo-geo-audit-skill
description: Run a unified SEO and GEO audit for a website, page, or domain. Use when the user asks for a full SEO audit, GEO audit, AI visibility review, EEAT review, entity audit, authority audit, or wants one prioritized report that combines technical findings, content quality, trust signals, and AI citation readiness.
---

# SEO GEO Audit Skill

Use this skill to produce one audit that covers both search performance and AI visibility.

This skill is designed for three common use cases:

- `Homepage audit`: quick diagnosis for a single URL
- `Site audit`: broader review across key templates and pages
- `Domain visibility audit`: strategic review including entity and authority signals

## What This Skill Covers

1. Technical SEO
   - crawlability
   - indexability
   - performance and rendering
   - security and trust headers
   - schema and metadata
   - mobile and accessibility risks

2. On-page SEO
   - title, meta description, headers
   - search intent alignment
   - content depth and structure
   - internal linking
   - media optimization

3. GEO and AI visibility
   - answer-first formatting
   - extractability and quotability
   - semantic clarity
   - AI crawler access signals
   - machine-readable brand and content signals

4. Trust, entity, and authority
   - author and editorial transparency
   - about, contact, and policy signals
   - organization identity consistency
   - entity disambiguation
   - third-party credibility and authority indicators

## Workflow

1. Define the scope.
   - single page
   - limited site crawl
   - domain-level strategic review

2. Start with the observable baseline.
   Collect factual findings from live pages, crawl data, page source, rendered output, and any available audit tooling.

3. Separate evidence from judgment.
   Label each item as:
   - `Observed`
   - `Assessment`
   - `Not verified`

4. Review the site in layers.
   - technical layer
   - on-page/content layer
   - GEO layer
   - entity/authority layer

5. Prioritize actions.
   - `P0`: blockers, trust failures, indexing failures, major performance issues
   - `P1`: meaningful ranking and citation improvements
   - `P2`: optimization and scale work

6. Present the result in the right audience mode.
   - `Boss mode`
   - `Operator mode`
   - `Specialist mode`

## Output Rules

- If the user writes in Chinese, answer in Chinese unless asked otherwise.
- Always begin with a short executive summary.
- Keep technical facts and strategic recommendations distinct.
- Do not invent data for backlinks, Search Console, server logs, or AI citation share.
- Mark unavailable inputs as `Not verified`.

## Audience Modes

### Boss mode

Use when the user asks for `老板版`, executive summary, or management briefing.

- short
- business impact first
- minimal jargon
- no long issue dumps

Read `references/output-template-zh-boss.md` before writing.

### Operator mode

Use when the user wants a practical roadmap.

- balanced detail
- clear priorities
- implementation-oriented language

Read `references/output-template.md` before writing.

### Specialist mode

Use when the user wants deep analysis.

- include assumptions
- include validation gaps
- include section-level scoring logic

Read `references/scoring-framework.md` before writing.

## Minimum Deliverable

Every audit should include:

- scope
- overall technical view
- content and GEO view
- entity and authority view
- top priorities
- missing data and validation notes

## References

- `references/scoring-framework.md`
- `references/output-template.md`
- `references/output-template-zh-boss.md`
