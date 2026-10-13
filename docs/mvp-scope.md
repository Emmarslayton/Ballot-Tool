# MVP Scope: Colorado Ballot Education

## MVP objective

Help an everyday Colorado voter move from a basic understanding of one ballot measure to a more informed view of its arguments, evidence, and documented campaign funding.

## Primary user journey

1. Select a ballot measure.
2. Read a plain-language overview.
3. Learn what a yes vote and a no vote mean.
4. Compare the major arguments made for and against the measure.
5. Expand a claim to inspect its sources, assumptions, and uncertainties.
6. Explore the committees documented as supporting or opposing the measure.
7. Inspect reported contributions and expenditures for those committees.
8. Follow links to original records.
9. Optionally record personal questions or trade-offs.

## Must-have capabilities

### 1. Measure overview
- Official measure title and identifier.
- Plain-language summary with editorial review.
- What changes and what does not.
- Meaning of yes and no.
- Official ballot text and Blue Book links.
- Official fiscal analysis link and concise explanation where feasible.

### 2. Arguments and evidence
- Major arguments for and against, clearly attributed.
- Claims separated into manageable units.
- Source links and relevant passages where available.
- Distinction between facts, estimates, predictions, interpretations, and unknowns.
- Clear indication when a claim is disputed or the available evidence is incomplete.

### 3. Funding transparency
- Committees associated with the measure and the evidence for each association.
- Committee type and stated purpose, where available.
- Reported contributions and expenditures for a clearly stated reporting period.
- Major contributors and payees within the defined scope.
- Original disclosure links and last-checked dates.
- Explicit handling of loans, in-kind transactions, refunds, transfers, and reporting-period differences.

### 4. Source transparency
- Source title, publisher or filer, publication/reporting date, source type, and URL.
- A short explanation of what the source supports.
- Data retrieval date for imported records.
- Known limitations and unresolved matches.

## Should-have capabilities, if time permits
- Search across the pilot measure's claims, committees, and source records.
- Simple contribution/expenditure timeline.
- Save personal questions or notes locally or in an account, depending on architecture and privacy decisions.

## Not in MVP
- Nationwide coverage.
- All candidates and elected officials.
- Full nonprofit, lobbying, corporate ownership, and grant funding graphs.
- Automatic truth scores, credibility rankings, political bias labels, or influence scores.
- A recommendation to vote yes or no.
- Unreviewed AI-generated summaries or conclusions.
- Real-time ingestion before the import and update process is understood.

## MVP quality requirements
- Every displayed financial total has a documented calculation and defined period.
- Transactions are not double-counted when summarizing contributions, expenditures, loans, transfers, refunds, or in-kind activity.
- Every committee-to-measure connection has a source and a relationship type.
- Similar names alone are not sufficient to merge people or organizations.
- Missing or ambiguous data is labeled.
- Core pages are keyboard accessible and usable on mobile.
- Content is understandable to a user with no prior campaign-finance knowledge.

## Proposed success criteria

Test with 5-8 people representative of the intended general audience. This is formative usability testing, not a statistically representative survey.

A participant should be able to:
- explain the measure's basic effect in their own words;
- describe at least one major argument on each side;
- open a source for a claim;
- explain what a displayed funding relationship does and does not establish; and
- identify an important uncertainty or limitation.

Record completion, errors, confusion, and participant feedback. Do not treat a user's political preference as a measure of product success.
