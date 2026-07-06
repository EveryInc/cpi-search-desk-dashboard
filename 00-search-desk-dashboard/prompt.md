# Build a Custom Dashboard Skill — Demo Prompts

This folder is a search consultant's desk: four data files plus a pre-built "search desk"
dashboard (`search-desk-dashboard.html` — open it in a browser before you do anything else).

- `active-searches.csv` — live mandates (client, role, strategy, stage, fee, target close date, status)
- `candidates.csv` — every candidate in play, which search they're on, stage, last contact, interest level
- `candidate-call-notes.md` — messy raw screening notes, one per candidate
- `client-feedback.json` — what clients said about candidates they've interviewed

The dashboard works. It's just not *yours* yet. The exercise: ask Claude to change it the way
you like it, then save that as a skill so every future rebuild comes out your way.
**You have 20 minutes.**

**Step 1 — see what you're working with (paste into Claude):**

> Read the four data files and search-desk-dashboard.html in this folder. Tell me how the
> dashboard is put together — what sections it has and which file each number comes from.

**Step 2 — make it yours (pick one or more, edit to taste — this is the point):**

*Design/Brand:*

> Restyle the dashboard: dark theme, CPI blue as the accent color, serif headers, tighter
> cards. It should look like ours, not like a template.

*Sections/Structure:*

> Move "Needs Me Today" to the very top and collapse the desk metrics into a single row.
> Add a "going stale" panel for candidates with no contact in 14+ days.

*Writing Style:*

> Rewrite every label and action item the way I'd actually say it — short, direct, no
> corporate speak. "Call Priya today — competing offer in play," not "Follow-up recommended."

**Step 3 — lock it in:**

> Save this as a skill called search-desk-dashboard: given these four files (or updated
> versions of them), rebuild the dashboard exactly this way — same design, same sections,
> same voice.

**Step 4 — prove it (new chat):**

> Use the search-desk-dashboard skill to rebuild my dashboard from the files in this folder.

Same dashboard, your way, on demand. That's the whole lesson: the first build is a
conversation, the skill makes it repeatable — point it at next Monday's files and your
dashboard comes back designed the way you like it.
