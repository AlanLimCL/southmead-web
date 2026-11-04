---
adr: 0001
status: accepted
date: 2026-11-04
session: "LoomWerk in-product disclaimer for role, skill and org chart configuration"
author: claude
tags: [adr, decision, loomwerk, disclaimer]
confidence: medium
review-by: ""
related: []
---

# ADR-0001: The disclaimer is written for outsiders and colleagues who see the labels but did not set them up

## Context

LoomWerk lets an admin name AI staff, pick profession-named skills such as "Accountant" or "Legal Reviewer", and group them in an org chart. The admin knows these are AI task templates. A colleague, auditor, client or regulator who sees the labels in an export, an email or a screenshot may read them as real qualifications, headcount or authority. The reader the note protects decides what the note must say and where it must sit.

## Options considered

- **Admins only.** A short clarity note on the dashboard is enough. The note need not say "AI staff, not employees".
- **Colleagues inside the client's company.** The note must explain that labels are task descriptions, read by people who did not choose them.
- **Outsiders and colleagues who see output.** The note must say the labels describe AI staff, not employees or qualifications, and must guide naming because outsiders never see the dashboard.

## Recommendation given

Outsiders and colleagues who see the labels but did not set them up. That is where a profession-named skill or an org chart reads as a claim, and it decides whether the note must say "AI staff, not employees".

## Decision

The user accepted the recommendation: outsiders and colleagues who see the labels but did not set them up.

## Consequences

- The note must state that these labels describe AI staff, not employees, qualifications or headcount.
- An in-product note cannot be read by outsiders, so its job is to guide the admin's naming before the labels travel. Prototypes P2 and P3 move ahead of P1.
- Placement should sit where names are typed, not only where they are viewed. This is the next decision.
- A follow-up product question is opened: whether the labels themselves should carry an "AI" marker in the places outsiders see them. That is a build change, not copy, and is parked for a later node.
