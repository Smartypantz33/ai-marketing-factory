---
name: positioning-messaging
description: Factory station 2 (strategy line). Builds a client's positioning statement and message house (core message, pillars, proof points, persona-specific angles) from the context pack and approved personas. Use when asked for positioning, a value proposition, key messages, a message house, taglines or "how should we talk about this client."
---

# Station: Positioning and messaging

**Line:** Strategy · **Needs:** research-personas · **Feeds:** content-calendar and every content and creative station

**Job:** Decide what the client stands for in the buyer's mind, then turn it into messages every other station can reuse.

---

## 1. Inputs

**Required**
- `context/brand-book.md`
- `context/offer.md`
- `context/personas.md` (approved, not a placeholder)
- `context/voice-and-tone.md`
- `context/guardrails.md`

**Optional**
- Competitor names or URLs (from the client or research-personas output)
- Client's own words about what makes them different (discovery notes, About page)
- An existing `context/positioning.md` to revise

If personas are still a placeholder, stop and recommend running `research-personas` first.

---

## 2. Steps

1. **Restate the buyer.** In one line per persona, restate the main fear and the main goal from `personas.md`.
2. **Name the frame of reference.** What category does the buyer put this client in? Choose the one the buyer would use, not the one the client prefers.
3. **Find the difference.** List what the client does that alternatives don't (from the inputs only). For each, ask: does the buyer care? Is it provable? Keep the ones that pass both.
4. **Write three positioning options.** Use the template: *For [target] who [need], [client] is the [frame of reference] that [key difference] because [reason to believe].* Make the three options genuinely different (e.g., lead with expertise, with care, with speed or simplicity).
5. **Recommend one.** Pick the strongest option and explain why in two sentences. The human decides.
6. **Build the message house** on the recommended option: one core message, three pillars, proof points under each pillar (from inputs only), and a "never say" list.
7. **Write persona angles.** For each persona: one headline, one supporting line, and one call to action, all in the client's voice.
8. **Run the guardrail check** (section 4), fix issues, then present with the review checklist (section 5).

---

## 3. Output template

Save as `outputs/<client-slug>/YYYY-MM-DD-positioning-messaging.md`

```markdown
Station: positioning-messaging
Date: YYYY-MM-DD
Context used: [list files]
Status: DRAFT – awaiting review

# Positioning and messaging: [Client]

## Buyer recap
- [Persona]: fear → goal

## Frame of reference
[Category the buyer uses]

## Differences that pass (cares + provable)
| Difference | Why the buyer cares | Proof |
|---|---|---|

## Positioning options
**A –** For ... who ..., [Client] is the ... that ... because ...
**B –** ...
**C –** ...

**Recommended:** [A/B/C] – [two-sentence reason]

## Message house
**Core message:** ...

| Pillar 1 | Pillar 2 | Pillar 3 |
|---|---|---|
| headline | headline | headline |
| proof point | proof point | proof point |
| proof point | proof point | proof point |

**Never say:** ...

## Persona angles
### [Persona 1]
- **Headline:**
- **Supporting line:**
- **Call to action:**
```

---

## 4. Guardrail check

- [ ] **Every proof point is real.** Each comes from the context pack or the client. No invented awards, years, numbers or testimonials. Gaps are marked `[NEEDS CLIENT INPUT: ...]`.
- [ ] **No superlatives we can't prove.** Avoid "best," "#1," "only," "guaranteed" unless documented.
- [ ] **No fear selling.** Name the buyer's fear honestly, but don't amplify it to pressure a decision.
- [ ] **Competitors are not named or disparaged** in client-facing lines.
- [ ] **Voice matches** `context/voice-and-tone.md`.
- [ ] **Follows `context/guardrails.md`.**

---

## 5. Review checklist (human)

- [ ] Could a competitor say the same positioning statement? If yes, it isn't different enough.
- [ ] Would the buyer use the chosen frame of reference?
- [ ] Is every proof point something the client can back up?
- [ ] Does each persona angle speak to that persona's main fear?
- [ ] Would the client be proud to say the core message out loud?

When approved: change status to `APPROVED – <date>`, commit, and propose the agreed positioning to your team for `context/positioning.md`.

---

## 6. Tool slot

**Job:** strategic synthesis and copywriting.
**Current tool:** see `playbook/tool-register.md` → Positioning and messaging.
**Default:** Claude. Optional add-on: a second AI model to generate a competing set of options for comparison.
