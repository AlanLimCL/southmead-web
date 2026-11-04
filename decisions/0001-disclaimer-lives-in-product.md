---
adr: 0001
status: accepted
date: 2026-11-04
session: "LoomWerk disclaimer for organizational structure, role and skill categorization"
author: claude
tags: [adr, decision]
confidence: high
review-by: ""
related: []
---

# ADR-0001: The disclaimer lives inside the product, on the Staff and Role Library pages, with one line under the Home org chart

## Context

A disclaimer is needed so the departments, roles and skills shown in LoomWerk are not misread as a real company's structure or as professional qualifications. Where the text lives decides which vocabulary the register allows (page names are banned in public broadcast and allowed in product and documentation channels), who reads it, and the sentence ceiling. This repo holds the Southmead website, not the LoomWerk product, so an in-product placement is a request to the product team rather than a change made here.

## Options considered

- **Inside the product, on the pages in the screenshots**: page names allowed; the reader is the client's administrator; the product team makes the change.
- **Public website beside screenshots**: the public ceiling applies; demo office names and task counts would need scrubbing first.
- **Product documentation**: a 25-word ceiling; the reader finds it only when they go looking.
- **More than one of the above**: several wordings to keep in step.

## Recommendation given

Inside the product, on the Staff and Role Library pages, with one line under the Home org chart. That is where the labels get set and changed, page names are allowed there, and the wording can stay short.

## Decision

Accepted as recommended (user, 2026-11-04).

## Consequences

- Draft C (illustrative sample framing for public screenshots) is pruned from this deliverable. Scrubbing demo names from marketing screenshots is a separate item, noted and not pursued here.
- Page names (Home, Staff, Role Library) and the product's own button wording ("Set live") may appear in the text.
- The reader is the client's administrator configuring the office. The 20-word sentence ceiling for a second-language reader stays the target.
- The final deliverable is a hand-over note to the product team plus a claim map. No code change lands in this repo.
- Still open for the interview: one block on both pages, or text tailored per page.
