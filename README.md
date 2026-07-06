# CPI — Build a Custom Dashboard Skill

**Workshop exercise · Level 3, Hour 1 (Intro to Cowork) · ~20 min**

A hands-on Claude Code exercise for CPI search consultants. Participants get a folder
containing four scattered data files — call notes, a mandate list, a candidate tracker, and
client feedback — plus a pre-built interactive "search desk" dashboard that joins them.
Their job: ask Claude to change the dashboard so it's designed the way *they* like it, then
save that as a skill they can reuse on fresh data later.

This is the recruiting-tailored version of Every's "Build a Custom Dashboard Skill"
exercise. The point isn't the dashboard — it's the muscle: **iterate on a real artifact with
Claude, then lock your taste into a skill so it's repeatable.**

---

## The Exercise

**Folder:** [`00-search-desk-dashboard/`](00-search-desk-dashboard/)

Open [`search-desk-dashboard.html`](00-search-desk-dashboard/search-desk-dashboard.html) in a
browser, then follow the step-by-step prompts in
[`prompt.md`](00-search-desk-dashboard/prompt.md): ask Claude to make a change to the
dashboard in the folder, and save that as a skill to reuse for later.

**A few things participants might change:**

- **Design/Brand** — colors, typography, dark mode, "make it look like ours"
- **Sections/Structure** — reorder panels, collapse metrics, add a new view
- **Writing Style** — labels and action items in their own voice

**What's in the folder:**
| File | What it is |
|---|---|
| `search-desk-dashboard.html` | The pre-built dashboard — the artifact they'll customize |
| `active-searches.csv` | 8 live mandates — client, role, strategy, stage, fee, target close, status |
| `candidates.csv` | 13 candidates in play, mapped to searches, with stage + last-contact + interest |
| `candidate-call-notes.md` | Messy first-person screening notes, one per candidate |
| `client-feedback.json` | Client interview feedback and ratings on submitted candidates |

All data is synthetic — no real PII. The files **cross-reference each other** — a call note
flags a candidate that the tracker says is stale, that the client feedback says is a "Strong
Yes" — and the dashboard is what those joins look like when they're pulled together.

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

- **Complexity:** Easy. The dashboard already exists, so nobody stalls at a blank page — the whole 20 minutes goes to iteration and the skill save.
- **Support level:** Self-directed. This cohort is AI-forward and will move quickly. Your job is to push them past the first tweak into changes that reflect *their* taste.
- **The mindset shift to name out loud:** In their GPTs, they paste text *in* and get text *out*. Here, Claude edits a *working tool* that lives in their files — and a skill makes that edit repeatable on next week's data. That's cowork. Say it explicitly.
- **The wow moment:** rerunning the `search-desk-dashboard` skill in a fresh chat and watching their design come back untouched — same brand, same sections, same voice. If someone's version looks genuinely theirs, have them show the room.
- **Where they'll get stuck:** a few will ask what the "right" change is. There isn't one — Design/Brand, Sections/Structure, and Writing Style are starting points, their judgment fills the rest. That ambiguity *is* the lesson.
- **If they finish early:** have them edit a row in `active-searches.csv` and rerun the skill to see the dashboard update; stack a second and third change into the skill; or ask Claude to rebuild it automatically every Monday. The automation ask is the bridge to the rest of Level 3.
- **Data confidence:** persona and all data are invented/representative, calibrated to CPI's public business profile (investment-professional search for PE/hedge/credit/RE/VC/family office) and a call-note-heavy workflow. No real candidates, clients, or comp.

---

*Built with Every Consulting's exercise generator.*
