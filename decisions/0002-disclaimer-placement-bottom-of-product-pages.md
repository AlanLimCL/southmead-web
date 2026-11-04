---
adr: 0002
status: accepted
date: 2026-11-04
session: "LoomWerk in-product disclaimer for role, skill and org chart configuration"
author: claude
tags: [adr, decision, loomwerk, disclaimer]
confidence: medium
review-by: ""
related: ["[[0001-disclaimer-audience-outsiders-and-colleagues]]"]
---

# ADR-0002: The note sits at the bottom of the product pages, as a standing info box

## Context

ADR-0001 set the audience as outsiders and colleagues who see the labels but did not set them up. Those readers never see the dashboard, so the note works by shaping what the admin types. The question was where the admin should meet the note: at the point of typing, as a page banner, or as one notice in Settings. The Role Library page already ends with an info box ("Keys and skills live in Settings, Connections & Keys"), so a bottom-of-page note has an existing pattern to match.

## Options considered

- **Point of typing.** Short wording under the Agent name and Role name fields, plus a tooltip on the org chart. Read at the moment it matters; most strings to maintain.
- **Banner at the top of the pages.** Four-sentence note above the content. Read once, then ignored.
- **Bottom of the product pages.** A standing info box in the same slot and style as the existing keys-and-skills box. Read after the content; consistent with the current UI.
- **One global notice in Settings.** Cheapest to ship; least likely to be read.

## Recommendation given

Point of typing, under the Agent name and Role name fields, with a one-line tooltip on the org chart card. Outsiders only ever see what gets typed, so the warning belongs where the typing happens.

## Decision

The user chose the bottom of the product pages. No reason was stated. Working assumption until corrected: the pages are the three where labels are set or shown, which are Role Library, Staff and the Home page's org chart section.

## Consequences

- The wording is one standing paragraph of three to four sentences, reusable across pages, in the style of the existing bottom info box. Prototype P2 is the closest fit; P3's per-field notes are no longer needed.
- The note is read after the admin has already seen the forms, so it must work as a reminder, not a prompt. It should name what outsiders see and ask for task-shaped names.
- Consistency with the existing info box means the note can carry a link, for example to the Role Library or to guidance, without a new UI pattern.
- If the user meant every product page, the same paragraph applies unchanged; only the paste locations grow.
