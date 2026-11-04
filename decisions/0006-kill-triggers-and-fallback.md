---
adr: 0006
status: accepted
date: 2026-11-04
session: "LoomWerk in-product disclaimer for role, skill and org chart configuration"
author: claude
tags: [adr, decision, loomwerk, disclaimer]
confidence: medium
review-by: "After the lawyer's review and after the first pilot's first-week log review"
related: ["[[0003-disclaimer-is-legally-operative]]", "[[0005-register-carve-out-only]]"]
---

# ADR-0006: Two triggers pull the page note back to the informational wording, and the owner makes the call

## Context

A formal, legally operative note on a product page can add exposure or friction that only shows after it ships. Without a kill rule agreed in advance, a complaint from a pilot client or a lawyer's objection becomes a debate at the worst moment. The fork was what result would make the note be pulled or rewritten, and who decides.

## Options considered

- **No kill rule.** Decide when a problem appears.
- **Two triggers, owner decides.** The lawyer says the page note adds exposure, for example by implying Southmead verifies or endorses the labels; or a pilot client or partner raises the note as friction in the first-week log review. On either, the page drops back to the informational wording in prototype P2 and the terms clause stays.

## Recommendation given

Two triggers, and the owner makes the call.

## Decision

The user accepted the recommendation: two triggers, and the owner makes the call. The interviewer reads "you" as the user, Alan, as owner.

## Consequences

- The fallback is pre-written: prototype P2, the informational four-sentence note. Only the page changes; the terms clause stays in force.
- Trigger one is checked when the lawyer's review returns. Trigger two is checked at the first pilot's first-week log review.
- The page note must avoid any wording that implies Southmead reviews, verifies or endorses the labels, since that is the exposure trigger one names. That statement belongs only in the terms clause, phrased as a negative.
