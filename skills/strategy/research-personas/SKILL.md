---
name: research-personas
description: Factory station 1 (strategy line). Researches a client's market and audience from the context pack and public sources, then drafts buyer personas with fears, needs, triggers and message cues. Use when starting work for a new client, when asked for personas, audience research or customer insight, or when the context pack has no agreed personas yet.
---

# Station: Research and personas

**Line:** Strategy · **Feeds:** positioning-messaging, content-calendar, every content and creative station

**Job:** Turn what we know about the client into a clear picture of who buys, why they hesitate, and what they need to hear.

---

## 1. Inputs

**Required**
- `context/brand-book.md` – what the client does, for whom, and where
- `context/offer.md` – services and service area
- `context/guardrails.md` – rules for claims, privacy and audience sensitivity

**Optional (use if present)**
- A filled-in `templates/client-intake.md` for this client
- The client's website, reviews pages or social accounts (public pages only)
- Notes from a discovery meeting with the client
- An existing `context/personas.md` to revise rather than replace

If a required input is still a placeholder, stop and tell the user which file is missing.

---

## 2. Steps

1. **Read the context pack.** Summarize in three bullets what the client sells, where, and to whom. Ask the user to confirm before continuing.
2. **Separate the buyer from the user.** Identify who *decides and pays* versus who *receives* the service. These are often different people. List both.
3. **Map the market.** From public sources and the context pack, note: the category the client competes in, 2–4 alternatives a buyer might choose instead (including "do nothing" or "do it ourselves"), and the moments that trigger a search for help.
4. **Draft 2–3 personas.** Use the output template below. Each persona must be grounded in something from the inputs; mark anything inferred as `(assumption – validate with client)`.
5. **Write the fear map.** For each persona, list what they're afraid of (practical, emotional, social) and what would reassure them.
6. **Pull message cues.** For each persona, write 3 phrases they would actually say about their problem, in plain language. Don't put marketing words in their mouths.
7. **List what to validate.** End with the 3–5 assumptions most worth checking with the client before they go into the context pack.
8. **Run the guardrail check** (section 4), fix issues, then present the output with the review checklist (section 5).

---

## 3. Output template

Save as `outputs/<client-slug>/YYYY-MM-DD-research-personas.md`

```markdown
Station: research-personas
Date: YYYY-MM-DD
Context used: [list files]
Status: DRAFT – awaiting review

# Research and personas: [Client]

## What the client sells, where, to whom
- ...

## Buyer vs. user
| Role | Who | What they care about |
|---|---|---|
| Decides and pays | | |
| Receives the service | | |
| Influences the decision | | |

## Market snapshot
- **Category:**
- **Alternatives a buyer considers:**
- **Trigger moments:**

## Persona 1: [Name, one-line description]
- **Who they are:**
- **Situation right now:**
- **Goal:**
- **Fears:** practical / emotional / social
- **What reassures them:**
- **Where they look for help:**
- **In their words:** "..." / "..." / "..."
- **Message cue:** the one thing they most need to hear

## Persona 2: ...

## Assumptions to validate with the client
1. ...
```

---

## 4. Guardrail check

Before showing the output, confirm each item and fix anything that fails:

- [ ] **No invented facts.** No made-up statistics, survey results, or "studies show." Any number must come from a named public source or the client.
- [ ] **No real people.** Personas are composites. No real names, photos, addresses or identifiable stories.
- [ ] **Respectful framing.** Personas describe situations, not stereotypes. No assumptions about health, income, family conflict or ability that aren't grounded in the inputs.
- [ ] **Assumptions are marked.** Anything not from the inputs is tagged `(assumption – validate with client)`.
- [ ] **Follows `context/guardrails.md`.**

---

## 5. Review checklist (human)

- [ ] Would the client recognize these people as their customers?
- [ ] Is the buyer clearly separated from the user?
- [ ] Are the fears specific enough to write a headline from?
- [ ] Do the "in their words" phrases sound like real people, not ads?
- [ ] Are the assumptions to validate the right ones to ask the client about?

When approved: change status to `APPROVED – <date>`, commit, and propose the agreed personas to your team for `context/personas.md`.

---

## 6. Tool slot

**Job:** desk research and synthesis.
**Current tool:** see `playbook/tool-register.md` → Research and personas.
**Default:** Claude with web search. Optional add-ons: review aggregators, Google Trends, Reddit/forum search, AI search engines for "what do people ask about…".
