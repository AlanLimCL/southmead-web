---
adr: 0003
status: accepted
date: 2026-11-04
session: "LoomWerk disclaimer for organizational structure, role and skill categorization"
author: claude
tags: [adr, decision]
confidence: medium
review-by: ""
related: ["[[0001-disclaimer-lives-in-product]]", "[[0002-disclaimer-covers-structure-and-professional-titles]]"]
---

# ADR-0003: The closing sentence states the user's responsibility to review and approve the configuration

## Context

The brief asked the disclaimer to end with a reminder that the configuration is subject to the user's own review. Two shapes were on the table. The register's audit rule (claim-audit walk, item 7) says Southmead's own copy states design properties, never client obligations: "your people stay in charge" passes, "you need a person in charge" does not. A stated responsibility is a client obligation, so it conflicts with that rule unless the owner overrides it for this line or counsel owns the wording.

## Options considered

- **Soft check, design-property voice**: "You own these settings and can change them at any time, so check them against how your business works." Passes the audit rule; carries no obligation.
- **Stated responsibility**: "Users are responsible for reviewing and approving all configurations before use." A client obligation; fails the audit rule as written; the usual shape of a legal disclaimer.

## Recommendation given

The soft check. The register's audit rule rejects client obligations in Southmead's own copy, and the brief asked for a reminder rather than a transfer of liability. If counsel later wants the responsibility form, it belongs in the licence terms, not on the screen.

## Decision

The user chose the stated responsibility (Alan, 2026-11-04), overriding the recommendation. No reason was given in the session; the record stands on the owner's word.

## Consequences

- The closing sentence carries a client obligation. This record is the backing for it in the claim map: `[Alan 2026-11-04]`, not a design-property claim.
- The audit rule is overridden for this one line only. It is not amended; any other asset still follows it.
- The sentence is legal language, which raises the weight of the legal-posture question (ADR-0004): an obligation counsel has not seen costs more wrong than absent.
- Wording default: second person, in the product's voice ("You are responsible for reviewing and approving these settings before you set staff live."), unless counsel prefers the third-person form.
- Draft E's closing sentence is the source; drafts A, B and D lose their soft-check endings.
