# Product Validation Plan

## Goal

Test whether a guided voter guide with expandable research helps everyday Colorado voters understand ballot measures and navigate evidence and funding information more effectively.

## Phase 1: Desk research

For one candidate pilot measure, collect:

- official ballot text and title;
- Colorado Blue Book analysis;
- official fiscal impact statement;
- major arguments from the Blue Book;
- source materials cited by supporters and opponents, where available;
- TRACER committee details and financial summaries;
- downloadable contribution and expenditure data relevant to the committee(s);
- links and evidence establishing why each committee is associated with the measure.

For every item, record its URL, publisher/filer, date or reporting period, retrieval date, and known limitations.

## Phase 2: Data feasibility test

Answer these questions before choosing the implementation architecture:

1. How can a measure be identified consistently?
2. What evidence links a committee to the measure?
3. Which TRACER records identify a committee, transaction type, amount, date, contributor/payee, and reporting period?
4. How are in-kind contributions, loans, repayments, refunds, and transfers represented?
5. Can imported transaction totals be reconciled with TRACER's own committee summaries?
6. How will duplicate records and amended filings be handled?
7. What identity-matching rules are safe for people and organizations?
8. Which data can be downloaded and processed reproducibly?
9. What needs manual review?

Deliverable: a short data feasibility report with examples, unresolved issues, and a recommendation on the pilot measure.

## Phase 3: Prototype

Create a low-fidelity page or clickable prototype containing:

- measure overview;
- yes/no effect explanation;
- arguments for and against;
- expandable claim evidence;
- committee and funding summary;
- original-source links.

Use real, cited content for one measure. Clearly label any placeholder or unverified data.

## Phase 4: Usability sessions

Recruit 5-8 people who are not campaign-finance specialists. Ask them to complete tasks without coaching:

1. Explain what the measure would change.
2. Find one argument from each side.
3. Open the source behind a specific claim.
4. Find out who contributed to a committee associated with the measure.
5. Explain what a financial relationship does and does not prove.
6. Identify something that remains uncertain.

Observe where people hesitate, misunderstand terminology, mistake correlation for coordination, or cannot find source material.

## Phase 5: Decision gate

Proceed to implementation if:

- the data links can be supported with documented evidence;
- the financial calculations can be reconciled with source summaries;
- users understand the distinction between arguments, evidence, and funding;
- the guided experience reduces confusion compared with navigating the sources separately; and
- the scope remains feasible for a solo portfolio project.

Otherwise, revise the pilot, narrow funding functionality, or adjust the experience before building the full application.
