# Shree Siddhi Engineering Enterprises — Company Website

> A ground-up digital revamp of a family-owned B2B engineering firm's company profile — from a scanned, blurred PDF to a structured, client-ready web presence.

**Live:** [Shree Siddhi Engineering Enterprises](https://shree-siddhi-engineering.vercel.app/)  
**Role:** Product Owner   
**Type:** Real-world client project (family business)

---

## The Problem

Shree Siddhi Engineering Enterprises is a Bhiwadi-based manufacturer serving clients like Hero MotoCorp, KEI Industries, and Mittal Forgings. Despite 20+ years of operational history, the company had no web presence — only a scanned PDF brochure with blurred images, generic copy, and no contact conversion path.

When a new firm was incorporated to carry the legacy forward, it was an opportunity to build the digital presence from scratch, the right way.

---

## My Role & Decisions

This project was driven end-to-end from a product ownership perspective:

**Discovery & audit**
- Reviewed the existing company profile (PDF) and identified gaps: outdated structure, grammatical errors, overclaiming language, no credibility signals, no conversion path
- Identified the target audience as B2B procurement managers and purchase officers — not general consumers

**Strategic decisions made**
- Chose a static single-file architecture — no CMS, no framework overhead. The business has no developer on staff, so maintainability without technical knowledge was a hard requirement
- Chose WhatsApp as the primary conversion channel over a traditional contact form — more appropriate for how Indian B2B buyers actually communicate
- Added a legacy/heritage section to bridge Supreme Techno Systems (est. 2004) with the new firm — builds immediate trust without misrepresenting the new entity
- Deliberately softened overclaiming copy ("zero tolerance for defects" → factual, measured language) based on the insight that B2B buyers trust specificity over superlatives
- Chose to show GST and MSME as placeholders rather than omit them — signals intent and removes friction for procurement teams doing vendor onboarding
- Added Google Business Profile link as a trust signal — third-party verification more credible than self-declared claims

**UX decisions**
- Sticky top bar with Call, Email, WhatsApp, and Google Business — visible at all times for procurement managers who want to act immediately
- Floating WhatsApp CTA + dedicated WhatsApp section — two-touch strategy for the highest-converting channel
- Mobile hamburger nav — the previous PDF had no mobile equivalent at all
- Contact form submits via `mailto` — fully functional with zero backend infrastructure

---

## What Was Built

| Section | Purpose |
|---|---|
| Sticky top bar | Instant access to all contact methods at all times |
| Hero + stats | First impression — credibility in 5 seconds |
| WhatsApp CTA | Primary conversion path |
| Our Journey | Heritage narrative — bridges old firm to new |
| About + Company Details | Factual grounding, registration info |
| Credentials | GST, MSME, Google Business — vendor onboarding signals |
| Why Choose Us | Differentiation without overclaiming |
| Products & Services | 6 categories with image placeholders |
| Infrastructure | Machine list — signals serious manufacturing capability |
| Our Clients | Social proof — Hero MotoCorp, KEI Industries, etc. |
| Contact + Enquiry Form | Secondary conversion path |

---

## Tech

Single-file static website — `index.html` with embedded CSS and JS.

| What | Choice | Reason |
|---|---|---|
| Fonts | Barlow + Barlow Condensed | Industrial feel, strong at display sizes |
| Color scheme | Navy `#0D1B2E` + Orange `#E8600A` | Bold & modern — avoids generic industrial grey |
| JS | Vanilla only | No dependencies = no maintenance overhead |
| Deployment | Vercel static | Zero-config, auto-deploys on push |
| Form | `mailto` handler | No backend needed, works immediately |

---

## Pending (Owned by Client)

- [ ] Add GSTIN — search `To be updated` in `index.html`
- [ ] Add MSME registration number — same
- [ ] Replace WhatsApp number with official WA Business number (4 instances)
- [ ] Add real product photos to replace placeholders

---

## Outcome

A fully client-ready static website replacing a scanned PDF — with a clear conversion strategy, credibility signals appropriate for B2B procurement, and zero ongoing infrastructure cost.

---

_Built for Shree Siddhi Engineering Enterprises, Bhiwadi, Rajasthan._  
_Contact: Vivek Mishra — shreesiddhiengineering23@gmail.com_
