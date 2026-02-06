# Binary Event Equity Screener -- Prompt for Claude AI

Paste everything below the dashed line into a new Claude AI conversation.

--------------------------------------------------------------------------------

Generate a professional equity research report identifying 8-15 US-listed public equities that have a specific, upcoming binary event within the next 1-9 months. Use web search extensively for every claim. Do not rely on training data for dates, prices, or event details.

A binary event is a single, discrete, time-bound decision by an external authority (court, regulator, agency, review board) or outcome of a pass/fail milestone (technology demonstration, clinical readout) that will materially re-rate the stock in one of two directions: significantly up or significantly down.

## What qualifies as a binary event

- An FDA Advisory Committee meeting, PDUFA decision, or Type A/B meeting outcome that determines a company's regulatory pathway
- A court verdict in a patent, antitrust, or class action case with billions at stake
- An FCC, DOE, NRC, EPA, or FAA regulatory decision (spectrum license, reactor approval, launch license, pipeline permit, contract award)
- A first-of-its-kind technology demonstration where success validates a business model and failure invalidates it (rocket test, satellite deployment, reactor criticality)
- A government contract down-select or award decision where a company is a finalist
- A clinical data readout with a binary trial design (met primary endpoint or did not)

## What does NOT qualify

- Routine quarterly earnings as the sole event
- Announced mergers or acquisitions pending regulatory close (merger arbitrage)
- Broad macro events affecting hundreds of stocks (tariff rulings, Fed rate decisions, trade policy)
- Vague catalysts ("AI adoption could accelerate," "management expects growth")
- Events that already occurred

Exception: if a specific binary event result will be disclosed on an earnings call (e.g., a trial verdict, contract award, or regulatory decision announced during the call), that qualifies because the underlying event is the catalyst, not the earnings themselves.

## Anchor example (match this quality bar)

uniQure N.V. (QURE) -- FDA Type A Meeting on BLA Pathway
Market Cap: approximately $1.2B | Sector: Biotechnology (Gene Therapy)
QURE held a Type A meeting with the FDA on January 9, 2026, to discuss the BLA pathway for AMT-130 (Huntington's disease gene therapy) after a prior Complete Response Letter. Meeting minutes, expected by early February 2026, will clarify whether QURE can pursue accelerated approval with existing data or must conduct a full Phase 3 controlled trial. Favorable outcome: accelerated pathway allowed, stock re-rates upward significantly. Unfavorable outcome: full Phase 3 required, adding years of delay and hundreds of millions in cost.

Every entry in the report should be at least this specific.

## Sector diversity requirement

Include stocks from at least 4 of these 7 categories. No single category may exceed 40% of total entries:

1. Biotechnology / Pharmaceuticals
2. Technology / Semiconductors
3. Aerospace / Defense
4. Energy / Nuclear / Utilities
5. Telecommunications / Media
6. Legal / Litigation-Driven
7. Financial / Regulatory

## Research sources to search

Search all of the following. Use specific search queries for each:

- FDA calendars: BioPharmCatalyst.com, CatalystAlert.io, Benzinga FDA Calendar -- focus on AdCom meetings, CRL resolutions, PDUFA dates for lead pipeline assets of clinical-stage companies. Limit biotech to 2-4 of the highest-impact events.
- Court dockets: search "[company] trial verdict 2026," "patent trial billion dollar ruling 2026," "antitrust ruling 2026 stock impact"
- Non-FDA regulatory: search "FCC spectrum license decision 2026," "DOE contract award 2026," "NRC reactor approval 2026," "FAA launch license 2026"
- Technology milestones: search "first launch 2026 stock," "demonstration test pass fail 2026," "proof of concept binary outcome 2026"
- Government contracts: search "contract down-select 2026," "sole source award protest 2026"
- Financial Substacks and forums: search "binary event" site:substack.com 2026, "binary catalyst" site:seekingalpha.com 2026, "binary outcome" stock catalyst 2026

## Analysis framework

For every stock, apply this five-step meta-cognitive reasoning procedure. Show all work explicitly.

**A. DECOMPOSE** -- Break the favorable-outcome probability into 3-6 independent sub-factors. Examples: scientific/technical merit, regulatory precedent, decision-maker track record, quality of evidence, procedural signals (priority review granted, motion to dismiss denied), competitive dynamics.

**B. SOLVE** -- Assign each sub-factor an explicit probability score (0.0 to 1.0) that it supports a favorable outcome. Include a 1-2 sentence rationale for each score. Use this calibration scale:
- 0.9-1.0: Near-certain favorable (overwhelming evidence, strong precedent)
- 0.7-0.8: Likely favorable (positive signals, some residual uncertainty)
- 0.5-0.6: Genuine coin flip (credible arguments on both sides)
- 0.3-0.4: Likely unfavorable (negative signals, not impossible to overcome)
- 0.0-0.2: Near-certain unfavorable (strong counter-evidence)

**C. VERIFY** -- Before proceeding, check each score for: factual accuracy (are dates and figures correct?), completeness (any missing sub-factors?), and cognitive bias (anchoring on narrative, confirmation bias from source material, recency bias). Correct any scores as needed.

**D. SYNTHESIZE** -- Combine sub-factor scores into a single weighted probability of favorable outcome (0.00-1.00). State the weighting rationale in 1-2 sentences.

**E. REFLECT**
- If P(Favorable) >= 0.80: state the primary risk that could invalidate the assessment
- If P(Favorable) is 0.50-0.79: identify which sub-factor(s) drive the uncertainty and what information would resolve it
- If P(Favorable) < 0.50: explicitly flag as "unfavorable outcome more likely" -- these are still worth including if the market appears to be mispricing the risk

## Report structure

### Section 1: Executive Summary Table

| # | Ticker | Company | Sector | Mkt Cap | Binary Event | Expected Date | P(Favorable) | Key Risk |
|---|--------|---------|--------|---------|--------------|---------------|--------------|----------|

Sort by expected event date, soonest first.

### Section 2: Methodology Note

3-4 sentences explaining the meta-cognitive framework, research sources consulted, and the date of research.

### Section 3: Detailed Stock Analyses

For each stock, use this template:

---

**[TICKER] -- [COMPANY NAME]**
Sector: [sector] | Market Cap: $[X.X]B | Price: $[X.XX] | Exchange: [NYSE/NASDAQ]

**The Binary Event**
[2-4 sentences. What is the event, when is it expected, who decides the outcome.]

**Favorable Outcome**
[2-3 sentences. What happens, estimated magnitude of stock impact if available.]

**Unfavorable Outcome**
[2-3 sentences. What happens, estimated magnitude of stock impact if available.]

**Meta-Cognitive Analysis**

A. DECOMPOSE
- Sub-factor 1: [name]
- Sub-factor 2: [name]
- Sub-factor 3: [name]
(3-6 sub-factors)

B. SOLVE
- Sub-factor 1: [0.XX] -- [rationale]
- Sub-factor 2: [0.XX] -- [rationale]
- Sub-factor 3: [0.XX] -- [rationale]

C. VERIFY
[1-3 sentences on corrections or bias checks performed]

D. SYNTHESIZE
Overall P(Favorable): [0.XX]
Weighting rationale: [1-2 sentences]

E. REFLECT
[2-3 sentences]

**Sources**
- [Source title](URL)
- [Source title](URL)

---

### Section 4: Disclaimer

"This report is for informational and educational purposes only. It does not constitute financial advice, a recommendation to buy or sell any security, or an offer to transact. Binary events are inherently unpredictable. Past regulatory, legal, or technical outcomes do not guarantee future results. Conduct independent due diligence before making any investment decisions."

## Formatting rules

- Professional, institutional research tone throughout
- No emojis anywhere
- No casual language or exclamation points
- Market caps to nearest $0.1B, probabilities to two decimal places, dates in Month DD, YYYY format
- Use horizontal rules between stock entries
- Bold section headers
- Where data is unavailable, write "Data unavailable" rather than estimating

## Quality checklist (verify before outputting)

Confirm all of the following before generating the final report:
- Every entry has a specific, dated binary event with an identifiable decision-maker
- No merger arbitrage plays
- No routine earnings as sole event
- No broad macro/tariff events
- At least 4 sector categories represented
- No sector exceeds 40% of entries
- Every entry has at least one cited source URL
- All 5 meta-cognitive steps (A-E) completed for every entry
- All prices, market caps, and dates sourced from current web search
- Zero emojis in the entire document
- 8-15 total stocks

Generate the report now.
