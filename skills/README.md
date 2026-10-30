# Skills: the 12 stations

| Line | Station | Status | Needs | Feeds |
|---|---|---|---|---|
| Strategy | `research-personas` | ✅ Built example | context pack | everything |
| Strategy | `positioning-messaging` | ✅ Built example | research-personas | everything |
| Strategy | `content-calendar` | Stub | positioning | content + creative lines |
| Content | `social` | Stub | calendar | report |
| Content | `blog-seo-geo` | Stub | calendar, positioning | email, social, report |
| Content | `email` | Stub | calendar, positioning | report |
| Creative | `ad-creative` | Stub | positioning, calendar | landing page, report |
| Creative | `video-short-form` | Stub | calendar, positioning | social, ads, report |
| Creative | `landing-page` | Stub | positioning, ads | report |
| Measure | `performance-report` | Stub | campaign data | insights |
| Measure | `insights-summary` | Stub | report | next brief, `/context` |
| Measure | `next-cycle-brief` | Stub | insights | calendar (next loop) |

## Building a stub

1. Open the stub's `SKILL.md` and read the two built examples first.
2. Replace every `BUILD:` line. Keep all six anatomy headings.
3. Update the `description` in the frontmatter and remove `[STUB – student to complete]`. Claude uses the description to decide when to use the skill, so say what it does and when to use it.
4. Test it on your client, review the output, and refine. Commit each improvement.

## Three ways to run a station

| Plan | How |
|---|---|
| **Free** | Open the station's `SKILL.md`, copy the text, paste it into your Claude Project chat, and ask Claude to run it. |
| **Pro: skills** | Zip the station's folder (e.g. `research-personas/`) and upload it in Claude under **Settings → Capabilities → Skills**. Then just ask for the job in your Project. |
| **Pro: Claude Code** | Open the repo in Claude Code and ask in plain English, e.g. *"Run the social station for week 1 of the calendar and save to outputs."* `CLAUDE.md` tells Claude where the stations are. |

Menu names in Claude can change; if Skills isn't where this says, search Claude's help centre for "upload a skill."

## Adding your own station

Your factory can grow past twelve. Copy a stub folder, rename it (lowercase, hyphens), and build it the same way. Add it to the table above and to `playbook/tool-register.md`.
