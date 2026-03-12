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

Assess these seven areas using `Strong`, `Moderate`, `Weak`, or `Unknown`:

1. Content Quality
2. Trust and EEAT
3. GEO Readiness
4. Entity Clarity
5. Authority Signals
6. Off-site Brand Mentions
7. Platform-Specific AI Readiness

If the user explicitly wants a number, use directional conversion only:

- Strong = 85
- Moderate = 70
- Weak = 50
- Unknown = excluded

## Combined Interpretation

- Strong technical + weak strategic: the site is crawlable, but not differentiated, referenced, or citable enough
- Weak technical + strong strategic: the message is strong, but delivery is suppressing results
- Weak technical + weak strategic: fix the baseline first, then strengthen content and brand signals
- Strong technical + strong strategic: move toward scale, testing, and monitoring

For management summaries, translate this into plain language:

- growth is being held back by technical friction
- infrastructure is stable but trust, entity, and platform visibility signals are underdeveloped
- both technical delivery and market visibility need work

## Strategic Visibility Checkpoints

Use these checkpoints when scoring the seven strategic areas.

### 1. Content Quality

- intent match
- page depth and completeness
- structural clarity
- conversion clarity

### 2. Trust and EEAT

- authorship and editorial clarity
- first-party evidence
- policy and legal transparency
- source quality and freshness

### 3. GEO Readiness

- answer-first formatting
- quotable blocks
- machine-readable packaging
- AI crawler accessibility cues

### 4. Entity Clarity

- organization identity consistency
- same brand naming across pages
- brand disambiguation
- about/contact/schema alignment

### 5. Authority Signals

- third-party credibility indicators
- trust-bearing references
- external validation of expertise
- domain-level reputation indicators

### 6. Off-site Brand Mentions

- LinkedIn company and founder presence
- Reddit mention frequency and sentiment
- YouTube channel or third-party transcript mentions
- Wikipedia / Wikidata presence
- GitHub, Product Hunt, Crunchbase, news, podcasts, and industry-community visibility

### 7. Platform-Specific AI Readiness

- ChatGPT and Bing compatibility
- Perplexity discussion and citation fit
- Google AI Overviews snippet and structure fit
- Gemini entity and Google ecosystem fit
- Bing Copilot freshness, IndexNow, and Microsoft-adjacent signals

## Priority Rules

Rank issues in this order:

1. indexing and crawl failures
2. security and trust blockers
3. rendering and major performance issues
4. metadata, schema, and structural issues
5. EEAT, entity, and authority reinforcement
6. off-site mention reinforcement and entity validation
7. GEO formatting, platform fit, and citation optimization

## Missing Data Rules

Mark as `Not verified` if you do not have:

- Search Console
- backlink tool data
- server logs
- field performance data
- AI citation monitoring

Do not guess backlink strength, branded demand, or citation share from page HTML alone.
Do not infer social/community visibility unless the source platform was explicitly checked.
