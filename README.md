# CPI — Build Your Search Desk Dashboard

**Workshop exercise · Level 3, Hour 1 (Intro to Cowork) · ~20 min build**

A hands-on Claude Code exercise for CPI search consultants. Participants paste one prompt and Claude Code reads four scattered files — call notes, a mandate list, a candidate tracker, and client feedback — and builds a single interactive "search desk" dashboard that surfaces what's about to cost them a fee today.

This is the recruiting-tailored version of Every's "Build a Custom Dashboard" exercise. The point isn't the dashboard — it's the muscle: **point Claude at your real chaos and let it synthesize.**

---

## The Exercise

**Folder:** [`00-search-desk-dashboard/`](00-search-desk-dashboard/)

Paste [`prompt.md`](00-search-desk-dashboard/prompt.md) into Claude Code with the four data files in the folder. First useful output in well under 12 minutes.

**Data files (all synthetic, no real PII):**
| File | What it is |
|---|---|
| `active-searches.csv` | 8 live mandates — client, role, strategy, stage, fee, target close, status |
| `candidates.csv` | 13 candidates in play, mapped to searches, with stage + last-contact + interest |
| `candidate-call-notes.md` | Messy first-person screening notes, one per candidate |
| `client-feedback.json` | Client interview feedback and ratings on submitted candidates |

The files **cross-reference each other** — a call note flags a candidate that the tracker says is stale, that the client feedback says is a "Strong Yes." The whole exercise is Claude connecting those dots.

---

## The Skill Exercise (used earlier in the hour)

**Folder:** [`01-candidate-submittals/`](01-candidate-submittals/)

Two synthetic resumes (Priya Nadkarni, Owen Brackett — the same candidates that later star in the dashboard data) plus step-by-step prompts in [`prompt.md`](01-candidate-submittals/prompt.md). Attendees draft a submittal blurb, tune the format once, save it as a `candidate-submittal` skill, and rerun it on the second resume in a fresh chat. This replaces building the skill on ASCII art — same arc, real artifact.

---

## Persona this was built around

**"Alex" — Search Consultant / VP at CPI.** Runs a desk of ~8 live mandates across PE, credit, real estate, hedge fund, VC, and family office. Already fluent with ChatGPT and custom GPTs for processing call notes. Comfortable with AI, brand new to *cowork* (Claude Code reading local files and building real artifacts).

**Pain point the exercise hits:** the morning scramble to reconstruct "what needs me today" from four disconnected sources — and the searches that quietly slip because nothing pulls it together.

---

## Facilitator Notes

- **Complexity:** Easy-Medium. The wow is fast; refinement fills the hour.
- **Support level:** Self-directed. This cohort is AI-forward and will move quickly. Your job is to push them past the first output into iteration.
- **The mindset shift to name out loud:** In their GPTs, they paste text *in* and get text *out*. Here, Claude reaches into *multiple files at once* and produces a *working tool*. That's cowork. Say it explicitly.
- **The wow moment:** the "Needs Me Today" panel correctly flags Priya Nadkarni (client "Strong Yes" + a competing offer ticking in the call notes) and the Halyard offer about to stall — insights that only exist when you join all four files. If someone's dashboard surfaces those, have them show the room.
- **Where they'll get stuck:** a few will ask for the "right" dashboard. There isn't one — the prompt lists ideas, their judgment fills the rest. That ambiguity *is* the lesson.
- **If they finish early:** point them at the stretch goals in the prompt — especially drafting the client-nudge emails and "rebuild this every Monday." The automation ask is the bridge to the rest of Level 3.
- **Data confidence:** persona and all data are invented/representative, calibrated to CPI's public business profile (investment-professional search for PE/hedge/credit/RE/VC/family office) and a call-note-heavy workflow. No real candidates, clients, or comp.

---

*Built with Every Consulting's exercise generator.*
