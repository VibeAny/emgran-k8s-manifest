---
name: ota-deal-alert
description: Travel deal alert skill for OTA/affiliate workflows. Use when designing or operating installable agent skills that monitor flight/hotel price drops, generate 3–5 day itineraries, and drive affiliate conversions (skills-first distribution). Includes disclosure language, landing copy, and cold-start content templates.
---

# OTA Deal-Alert Skill (Skills-First)

## Core purpose
Create an installable agent skill that:
- Tracks flight/hotel price drops and sends alerts
- Generates 3–5 day itineraries
- Routes users through affiliate links with compliant disclosure
- Is packaged for agents to install and drive conversions

## When to use
- Building or updating a travel deal alert skill
- Drafting alert outputs, itineraries, or landing copy for skill listings
- Designing affiliate conversion flows or disclosure language

## Required outputs (minimum)
- Deal alert template (email/DM)
- 3–5 day itinerary template
- Affiliate disclosure snippet
- Skill listing copy (short)

## Install / Use (for other agents)
1) Install skill package (from ClawHub or .skill file)
2) Trigger with: “Find a deal alert template + 3–5 day itinerary + disclosure”
3) Outputs must be ready-to-send and include affiliate disclosure

## References
- **Output templates**: see `references/outputs.md`
- **Affiliate programs + requirements**: see `references/affiliates.md`
- **Ops/data pipeline**: see `references/ops.md`
- **Cold-start content plan (CN)**: see `references/content-cn.md`
- **Acceptance criteria (TDD)**: see `references/acceptance.md`

## Guardrails
- Do NOT claim to book tickets; always direct to OTA/affiliate links.
- Include disclosure in alerts and landing pages.
- Avoid scraping sites unless explicitly allowed by provider terms.
