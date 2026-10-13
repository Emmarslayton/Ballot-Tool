# Discovery: Colorado Ballot Education

## Product vision

Help Colorado voters understand ballot measures, examine arguments and evidence, explore campaign funding, and make their own informed decisions with confidence.

## Problem statement

Voters can access official ballot information and campaign-finance disclosures, but understanding an issue often requires moving between separate sources, interpreting unfamiliar terminology, and connecting records that are not organized around a voter's questions.

The product should reduce that research burden without telling people how to vote.

## Primary audience

Everyday Colorado voters who want to understand ballot measures but have limited experience with campaign finance, policy analysis, or investigative research.

## Core user needs

1. Understand what a ballot measure would change and what a yes or no vote means.
2. Understand the main arguments for and against the measure.
3. Explore the evidence, assumptions, and uncertainties behind specific claims.
4. See documented campaign-funding information connected to the measure.
5. Verify important information using original sources.
6. Organize questions and trade-offs without receiving a prescribed voting recommendation.

## Product approach

A guided voter guide with an expandable research layer. The default experience should be clear and approachable. Users can open deeper layers for source passages, fiscal analysis, committee records, contributions, expenditures, and documented relationships.

## Differentiation hypothesis

Official sources already provide ballot text, summaries, arguments for and against, and fiscal analysis. The product's value is not simply reproducing those materials. Its hypothesis is that voters benefit from a connected research experience linking:

- the measure and its legal effect;
- arguments made by identifiable sources;
- evidence and assumptions relevant to those arguments;
- committees and their documented positions;
- reported contributions and expenditures; and
- original records that let users verify each connection.

This is a hypothesis to validate, not an established product advantage.

## Trust principles

- Do not recommend a yes or no vote.
- Do not imply both sides have equally strong evidence when they do not.
- Distinguish legal effects, documented facts, estimates, predictions, interpretations, and unknowns.
- Treat funding as context, not proof that a claim is true or false.
- Attribute arguments and contested interpretations to their sources.
- Show dates, reporting periods, source links, and relevant limitations.
- Do not infer relationships from similar names alone.
- Make data gaps visible; absence of a record in the product is not proof that no relationship exists.

## Initial scope

The first release will cover a small pilot set of statewide Colorado ballot measures from the November 2026 election. Start with one measure for the first end-to-end prototype, then expand only after the data model and user experience have been validated.

## Out of scope for the first release

- Other states or nationwide election coverage.
- Every candidate and race.
- Comprehensive tracking of all nonprofit, lobbying, corporate, or indirect funding.
- Automated political bias, credibility, or influence scores.
- Personalized vote recommendations.
- Social feeds, comments, and user-generated political debate.
- Unreviewed AI-generated verdicts on claims.

## Key assumptions to test

1. Voters struggle to connect information across official ballot resources and campaign-finance records.
2. A guided sequence is easier for general audiences than starting with a database search or network graph.
3. Voters find source-linked funding context useful when it is explained without implying motive.
4. Relevant committees and their reported financial records can be linked to a ballot measure with a defensible method.
5. The experience can explain evidence and uncertainty without overwhelming users.

## Discovery exit criteria

Do not commit to full implementation until:

- one measure can be researched end-to-end;
- the source-to-measure and committee-to-measure relationships are documented;
- the main financial summaries can be reproduced from source records;
- the prototype's explanations can be verified against original sources; and
- a small usability test shows target users understand the measure and can find supporting documentation.
