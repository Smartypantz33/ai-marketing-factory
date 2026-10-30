# AI Marketing Factory

A repeatable marketing operating system you can point at any client. Shared context goes in, standardized stations turn it into assets, a human approves the work, and the results make the next cycle better.

**The process is the asset. Tools plug into slots.**

This repo is your factory. You keep it after the course and can use it to run your own agency, bring it to an employer, or point it at a side hustle.

---

## How the factory works

```
 Context pack  ──►  Strategy line  ──►  Content line  ──►  Creative line  ──►  Review gate  ──►  Delivery
 (/context)         research,           social,            ad creative,        (checklist in       assets +
                    positioning,        blog/SEO/GEO,      video,              every skill)        report
                    calendar            email              landing page
                                                                                                     │
        ▲                                                                                            │
        └──────────────  Measure line: performance report → insights → next-cycle brief  ◄──────────┘
```

| Layer | Where it lives | What it does |
|---|---|---|
| Foundation | `/context` | Brand book, personas, positioning, voice, offer, guardrails. Synced from your team context repo. |
| Agency HQ | Your Claude Project | Project instructions + context files loaded as knowledge. The no-code way to run the factory. |
| Workshop | This repo + Claude Code | Permanent home and version history. Claude Code runs skills across these files. |
| Production lines | `/skills` | 12 stations across 4 lines. Every station uses the same anatomy. |
| Review gate | Inside every skill | Nothing ships without your approval. |
| Delivery and loop | `/outputs` → `/context` | Assets go to the client; learnings update the context pack. |

---

## Folder map

```
ai-marketing-factory/
├── README.md                 You are here
├── CLAUDE.md                 Rules Claude Code reads every session
├── PROJECT-INSTRUCTIONS.md   Paste into your Claude Project's instructions
├── context/                  Your client's context pack (synced from the team repo)
├── skills/                   The 12 stations
│   ├── strategy/             research-personas, positioning-messaging, content-calendar
│   ├── content/              social, blog-seo-geo, email
│   ├── creative/             ad-creative, video-short-form, landing-page
│   └── measure/              performance-report, insights-summary, next-cycle-brief
├── templates/                Agency-of-One: intake, onboarding, brief, report
├── outputs/                  Everything the factory produces, filed by client and date
└── playbook/                 How to run, sell and replicate your factory + tool register
```

---

## Station anatomy

Every skill in `/skills` follows the same six parts. Learn it once, build twelve times.

1. **Inputs** – which context files and brief details the station needs
2. **Steps** – what the station does, in order
3. **Output template** – the exact shape of what comes out
4. **Guardrail check** – claims, privacy, AI disclosure, audience sensitivity
5. **Review checklist** – what a human checks before approving
6. **Tool slot** – the job this station does, and which tool currently does it (see `playbook/tool-register.md`)

Two stations come fully built as examples: `strategy/research-personas` and `strategy/positioning-messaging`. The other ten are stubs for you to build.

---

## Quick start

1. **Make your copy.** On this repo's GitHub page, click **Use this template → Create a new repository**. Name it `ai-marketing-factory`, set it to **Private**, and create it.
2. **Add your context.** Copy the files from your team context repo into `/context` (see `context/README.md`).
3. **Set up your Claude Project.** Create a new Project in Claude, paste `PROJECT-INSTRUCTIONS.md` into its instructions, and upload the files from `/context` as knowledge.
4. **Run your first station.** In your Project, ask: *"Run the research-personas station for our client."* Paste or upload `skills/strategy/research-personas/SKILL.md` if you're not using skills yet.
5. **Save and commit.** Save the output into `/outputs` and commit it with a short message describing what changed.

**On Claude Pro?** You can upload each station as a skill (zip the station's folder) and later run the whole repo from Claude Code. **On the free plan?** Everything still works: paste the SKILL.md text into your chat and run the steps by hand.

---

## Rules of the factory

- **Context first.** Every station reads `/context` before it writes anything. Bad context, bad output.
- **Stations name jobs, not tools.** Swap tools in the tool register, not in the process.
- **Nothing ships without review.** The checklist is part of the station, not an afterthought.
- **Every cycle teaches the factory.** Insights go back into `/context` so the next run is better.
- **Commit often.** Your commit history is your factory's version history and your proof of work.
