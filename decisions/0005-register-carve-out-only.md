---
adr: 0005
status: accepted
date: 2026-11-04
session: "LoomWerk in-product disclaimer for role, skill and org chart configuration"
author: claude
tags: [adr, decision, loomwerk, disclaimer, register]
confidence: medium
review-by: "When the lawyer's wording comes back: confirm the page note still only points to the terms"
related: ["[[0003-disclaimer-is-legally-operative]]", "[[0004-page-note-points-to-licence-terms]]"]
---

# ADR-0005: The register records the carve-out only; the wording itself stays outside the register

## Context

ADR-0003 made the note legally operative, which conflicts with the claim register's rule that a design property never becomes a client obligation. ADR-0004 put the full wording in the licence terms. The fork was whether the wording also enters the register as a new approved claim, or whether the register only records a carve-out that legal text is governed by the licence terms and not by the obligation rule.

## Options considered

- **Enter the register with the carve-out recorded.** One entry, one owner, quotable in the user guide and support replies. The page and the terms cannot drift.
- **Carve-out recorded only.** The register's decision ledger records that legal disclaimer text is governed by the licence terms and sits outside the register's claim scope. The wording lives in the terms; the page points to it.
- **Ship outside the register with no record.** The next audit flags the text and nobody owns it.

## Recommendation given

Enter the register, with the carve-out recorded, so the asset pipeline's gate does not flag the text and the page and terms cannot diverge.

## Decision

The user chose the carve-out recorded only. The interviewer's reading: the wording does not become a register claim; a decision record carves legal disclaimer text out of the "no client obligation" rule and names the licence terms as its home. No reason was stated.

## Consequences

- The licence terms clause is the single source of the wording. The lawyer owns it. The page note carries the minimum operative wording and the pointer line, so there is little to drift.
- A register decision record is owed, in the register's own ledger, saying: legal disclaimer text on product pages and in the licence terms is governed by the terms, is outside the claim register's scope, and the obligation rule does not apply to it. That record is written in the register's workspace, not in this repo.
- The asset pipeline's register gate may still flag the page text on audit. The carve-out record is what the auditor cites to clear it.
- Support replies and the user guide may not quote the wording as an approved claim. They point to the terms instead.
