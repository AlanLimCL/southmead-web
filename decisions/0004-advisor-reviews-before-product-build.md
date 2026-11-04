---
adr: 0004
status: accepted
date: 2026-11-04
session: "LoomWerk disclaimer for organizational structure, role and skill categorization"
author: claude
tags: [adr, decision]
confidence: high
review-by: ""
related: ["[[0003-closing-sentence-is-a-stated-responsibility]]", "[[0002-disclaimer-covers-structure-and-professional-titles]]"]
---

# ADR-0004: The team advisor reviews the four sentences before the product team builds them in

## Context

Two of the four sentences are legal in character: the professional-title line (ADR-0002) and the stated-responsibility line (ADR-0003). The register records that no claim has had counsel review; the reviewer is the Southmead team advisor, with audit-trail and data claims first and trial and licence terms second in the queue (open item OI-07). The product team needs time to build the change in any case.

## Options considered

- **Advisor reviews first, one short item ahead of the product build**: the obligation and title sentences are seen by counsel before a client sees them; a small calendar cost.
- **Ship now as a clarification, join the counsel queue afterwards**: faster to the screen; an obligation sentence a client reads before counsel does.

## Recommendation given

The advisor reviews first. A review of four sentences costs little on the calendar, and an obligation sentence that counsel has not seen costs more wrong than absent.

## Decision

Accepted as recommended (user, 2026-11-04).

## Consequences

- The deliverable becomes a review packet for the team advisor: the four sentences, the Home one-liner, and a note on which two lines are legal in character, followed by the hand-over note to the product team once the advisor signs off.
- The advisor may change the responsibility sentence's form (second person or "Users"); the record of ADR-0003 allows either.
- Nothing ships to the product team until the advisor's reply. The product build is not blocked from being scheduled.
- This disclaimer joins the legal-review queue as its own item, ahead of the product build and separate from the register's existing priorities.
