# Future Interns – Prompt Engineering Task 1
# Brewed Bliss Cafe — AI Website Copy Generator (Prompt Engineering System)

A structured AI prompt engineering system that generates complete, ready-to-use website copy for local businesses. Built using **Brewed Bliss Cafe** (Jubilee Hills, Hyderabad) as the primary case study, with the same prompt templates tested across two additional business types (a dental clinic and a gym) to prove reusability.

Built for the **Future Interns 2026 — Prompt Engineering Internship**.

---

## Business Chosen

| | |
|---|---|
| **Name** | Brewed Bliss Cafe |
| **Type** | Specialty cafe — coffee, bakes, work-friendly space, private events |
| **Location** | Jubilee Hills, Hyderabad, India |
| **Audience** | Young professionals, students, work-from-café regulars |

This is a fictional business created for the purpose of this internship project.

---

## What This System Generates

- **Homepage Copy** - Headline, sub-headline, intro section
- **Services Page Content** - Service names, what's included, pricing, why-choose-this copy
- **CTA Sections** - Location-based CTA, trust-building CTA, urgency/booking CTA
- **Tone Adaptation** - Every prompt supports friendly / professional / confident tone, tested across 3 different business types

---

## Prompt Logic

Every prompt in this system follows the same five-part structure:

1. **Role** - assigns the AI a specific expert role (e.g. "You are a website copywriter for small businesses")
2. **Variables** - business name, type, location, audience, and tone are passed in as fill-in fields (e.g. `[BUSINESS_NAME]`, `[TONE]`), so the same prompt works for any client
3. **Rules** - explicit constraints: word limits, banned generic phrases ("world-class", "crafted with love", "passionate"), required structure
4. **Tone guide** - defines exactly what friendly / professional / confident means in terms of sentence length, word choice, and register, so the AI doesn't blend tones
5. **Output format** - a fixed structure (e.g. `HEADLINE: / SUB-HEADLINE: / BUTTON:`) so every output is copy-paste ready for a real website

This structure is what keeps the output **business-specific instead of generic** — every prompt requires real details (actual menu items, actual address, actual price range) rather than letting the AI default to filler language.

---

## Reusability — Tested Across 3 Business Types

To prove the prompt system is adaptable for multiple clients, every prompt was run unchanged (only variables swapped) against three different businesses:

| Business | Type | Tone |
|---|---|---|
| Brewed Bliss Cafe | Cafe | Friendly |
| Apollo Dental Clinic | Clinic | Professional |
| FitForce Gym | Gym | Confident |


---

## Tool Used

Claude
Chatgpt
Lovable

---

## Key Features Demonstrated

- ✅ Clear, benefit-driven website copy — every output leads with what the customer gains
- ✅ Business-specific language — real locations, real menu/service items, real ₹ pricing
- ✅ Strong calls-to-action — every CTA includes a heading, supporting copy, and an action-oriented button label
- ✅ Adaptable prompts — the same 8 prompts work for any local business by changing 4–5 variables
- ✅ Content ready for real websites — structured output can be pasted directly into website builders (Lovable, Framer, v0, Wix) or a hand-coded site

---

## Final Deliverable

- Complete AI-generated website copy set for Brewed Bliss Cafe (homepage, services, CTAs)
- 8 structured, reusable prompt templates
- Generated outputs for 3 different business types proving adaptability
- This README

---

*This project was completed as part of the Future Interns 2026 Prompt Engineering Internship.*
