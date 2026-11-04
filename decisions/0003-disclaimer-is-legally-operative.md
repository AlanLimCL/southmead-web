---
adr: 0003
status: accepted
date: 2026-11-04
session: "LoomWerk in-product disclaimer for role, skill and org chart configuration"
author: claude
tags: [adr, decision, loomwerk, disclaimer, legal]
confidence: low
review-by: "Before the wording ships: lawyer review and a claim-register amendment record"
related: ["[[0001-disclaimer-audience-outsiders-and-colleagues]]", "[[0002-disclaimer-placement-bottom-of-product-pages]]"]
---

# ADR-0003: The note is a legally operative disclaimer meant to limit Southmead's liability

## Context

ADR-0002 placed the note as a standing info box at the bottom of the product pages. The fork was whether that note is informational, in the product's own voice, or legally operative, meant to limit Southmead's liability for how a client's role, skill and org chart labels portray the client's organisation. The Southmead claim register, as installed, marks no claim as legally reviewed and forbids wording that turns a design property into a client obligation.

## Options considered

- **Informational notice.** Friendly voice, register capture and the owner's sign-off only. The operative wording lives in the licence terms.
- **Legally operative disclaimer.** Formal voice on the page. Needs a lawyer's review before it ships, a register amendment, and a matching clause in the licence terms for the page note to carry weight.

## Recommendation given

Informational, with the operative wording living in the licence terms, not on the page. An info box at the bottom of a dashboard is weak as a legal shield, and the register forbids wording that shifts obligations onto the client.

## Decision

The user chose a legally operative disclaimer meant to limit Southmead's liability. No reason was stated.

## Consequences

- Prototype P4 becomes the base. The tone is formal. P2's reminder sentence about what outsiders see can be kept as one line inside it.
- The wording allocates responsibility for the labels to the licensee. That conflicts with the register's rule that a design property never becomes a client obligation, so a register amendment record is needed, not only a capture.
- A lawyer must review the wording before it ships. Nothing in this session is legal advice; it is a business draft for that review.
- The page note should point to a clause in the licence terms that carries the full wording. Whether it does is the next decision.
- The confidence on this record is low because the interviewer's recommendation was overridden and the enforceability of a page-level disclaimer is a legal question outside this session's competence.
- A profession-named skill set keeps the exposure higher regardless of the wording. Renaming skills to task names is noted as an open product item, not a decision in this session.
