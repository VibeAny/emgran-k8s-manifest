# Project Tasks — Agent Skills Affiliate Platform

## Core Strategy
- [x] Define core path: installable agent skills → traffic → conversion → affiliate commissions (cross-domain scaling)

## Product (OTA Deal-Alert Skill — Skills-First)
**Priority: P0**
- [x] Finalize MVP spec with skills-first distribution baked in (architect draft received)
- [x] Define data sources + affiliate programs shortlist (ops/ba drafts received)
- [ ] Build Skill package v0.1 (travel deals + itinerary + disclosure) — draft skeleton created
- [x] Create landing page copy for Skill listing (skills-first positioning) (frontend draft received)
- [ ] Draft disclosure/terms snippets for skills output

## Distribution (ClawHub + Agent Ecosystem — Core Path)
**Priority: P0**
- [ ] Define differentiation: deal alerts + itinerary + affiliate tracking
- [ ] Publish Skill to ClawHub (name TBD)
- [ ] Add install guide + example prompts
- [ ] Create “skills-first” distribution playbook (how agents install, drive traffic, convert)
- [ ] Audit existing travel booking skills (done: low installs)

## MCP Service (trip-deals-mcp)
**Priority: P0**
- [ ] Define MCP API (search / deals / itinerary)
- [ ] Implement MCP service (repo: VibeAny/trip-deals-mcp)
- [ ] Deploy to k8s (config: ~/.kube/config.petaverse.devops)
- [ ] Add auth, rate limits, logging

## Ops/Data
**Priority: P1**
- [x] Flight price alert pipeline (Kiwi/Travelpayouts/Skyscanner) (ops draft received)
- [x] Hotel price alert pipeline (Booking/Agoda) (ops draft received)
- [ ] Alert rules + de-dup logic

## Growth & Content
**Priority: P1**
- [x] Cold-start content plan (Japan + Thailand) [drafted]
- [x] Newsletter template (weekly deals) (bops draft received)
- [ ] Example deal alerts + itineraries for Skill demo
- [x] Toutiao (今日头条) account growth plan for AI/OpenClaw use-cases (bops)

## Business & Legal
**Priority: P2**
- [ ] Affiliate disclosure wording
- [ ] Affiliate program applications (Trip.com, Agoda, Expedia/Partnerize)
- [ ] Decide entity strategy (budget constraints)

## Team Tasks (Assigned)
- [x] Architect: MVP spec (skills-first)
- [x] Frontend: OTA landing page copy (skills listing version)
- [x] Ops: OTA price-alert pipeline spec
- [x] BA: affiliate program comparison + requirements
- [x] Bops: cold-start content plan

## Process (Agile + TDD + QA)
- [ ] Define iteration cadence + standup schedule
- [ ] Define role-based pipeline ownership (Product/Arch/Frontend/Ops/BA/Bops/QA)
- [ ] TDD rule: each dev task must include tests before implementation
- [ ] QA rule: QA validates acceptance criteria before task closes

## Notes
- Keep outputs aligned to skills-first distribution model.
- Standups are used for cross-pipeline sync and blockers.
