---
adr: 0004
status: accepted
date: 2026-11-04
session: "LoomWerk in-product disclaimer for role, skill and org chart configuration"
author: claude
tags: [adr, decision, loomwerk, disclaimer, legal]
confidence: medium
review-by: ""
related: ["[[0003-disclaimer-is-legally-operative]]"]
---

# ADR-0004: The page note points to a clause in the licence terms that carries the full wording

## Context

ADR-0003 made the note legally operative. A footer note the client never agreed to is weak on its own, while a clause accepted at activation is what a lawyer can rely on. The fork was whether the three-to-four-sentence page note must do all the legal work itself, or whether it points to a clause in the licence terms.

## Options considered

- **Standalone.** The page sentences carry the whole wording. Denser text on the page; nothing to add to the terms.
- **Point to the terms.** The page keeps three to four sentences and ends with "See the Licence Terms, section X". The terms carry the full clause.

## Recommendation given

Point to the terms. The page stays readable and the lawyer has one place to make the wording bite.

## Decision

The user accepted the recommendation, in these words: point to the terms. The page keeps three to four sentences and ends with "See the Licence Terms, section X", and the terms carry the full clause.

## Consequences

- Two deliverables: the page note, three to four sentences ending with the pointer line, and a short terms clause for the lawyer to finish. The section number is a placeholder until the terms are numbered.
- The page note can stay readable. The dense allocation of responsibility moves to the terms clause.
- The licence terms must exist as a document the client accepts at activation. If no such document is on record yet, that gap is the first thing to close.
- The spelling is "licence" as the noun, per the register, in both the note and the pointer line.
