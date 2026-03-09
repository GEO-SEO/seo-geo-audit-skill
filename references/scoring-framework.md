# Scoring Framework

Use this framework to combine observable site findings with strategic visibility assessment.

## Presentation Modes

- `Boss mode`: use simple bands such as `Strong`, `Medium`, `Weak`
- `Operator mode`: use score ranges and priority tiers
- `Specialist mode`: include section-level scoring logic and validation notes

## Layer 1: Technical Health

Primary inputs:

- crawlability and indexability
- performance and rendering
- security and trust signals
- metadata and schema quality
- mobile and accessibility blockers

Suggested interpretation:

- `90-100`: strong technical baseline
- `75-89`: healthy but with meaningful weaknesses
- `60-74`: performance likely constrained
- `<60`: major blockers

## Layer 2: Strategic Visibility

Assess these five areas using `Strong`, `Moderate`, `Weak`, or `Unknown`:

1. Content Quality
2. Trust and EEAT
3. GEO Readiness
4. Entity Clarity
5. Authority Signals

If the user explicitly wants a number, use directional conversion only:

- Strong = 85
- Moderate = 70
- Weak = 50
- Unknown = excluded

## Combined Interpretation

- Strong technical + weak strategic: the site is crawlable, but not differentiated or citable enough
- Weak technical + strong strategic: the message is strong, but delivery is suppressing results
- Weak technical + weak strategic: fix the baseline first, then strengthen content and brand signals
- Strong technical + strong strategic: move toward scale, testing, and monitoring

For management summaries, translate this into plain language:

- growth is being held back by technical friction
- infrastructure is stable but trust and visibility signals are underdeveloped
- both technical delivery and market visibility need work

## Priority Rules

Rank issues in this order:

1. indexing and crawl failures
2. security and trust blockers
3. rendering and major performance issues
4. metadata, schema, and structural issues
5. EEAT, entity, and authority reinforcement
6. GEO formatting and citation optimization

## Missing Data Rules

Mark as `Not verified` if you do not have:

- Search Console
- backlink tool data
- server logs
- field performance data
- AI citation monitoring

Do not guess backlink strength, branded demand, or citation share from page HTML alone.
