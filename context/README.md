# Context pack

This folder is the foundation of your factory. Every station reads it before producing anything. **Same context in, comparable output out.**

The files here are placeholders. The real versions come from your **team context repo**, which your team builds together so everyone's factory starts from the same baseline.

| File | What it holds |
|---|---|
| `brand-book.md` | The client's brand: story, values, visual identity notes, what they do and don't do |
| `personas.md` | Who the client serves, what they fear, what they need to hear |
| `positioning.md` | Category, difference, proof, positioning statement |
| `voice-and-tone.md` | How the brand sounds: do/don't word lists, sample lines |
| `offer.md` | Services, service area, process, pricing (only what the client has confirmed) |
| `guardrails.md` | Rules on claims, privacy, AI disclosure and audience sensitivity |

## How to sync from your team context repo

Your team context repo has one owner per change (see its README). When a teammate announces an update:

1. Open your team context repo on GitHub and open the changed file.
2. Click the **Copy raw file** button (or **Raw**, then select all and copy).
3. In **this** repo, open the same file in `/context`, click the pencil icon, paste over the old content, and commit with a message like `Sync personas from team repo (v2)`.
4. Re-upload the changed file to your Claude Project's knowledge, replacing the old version.

**Check:** the version line at the top of each file should match the team repo's `CHANGELOG.md`.

## Rules

- Don't change these files on your own. Context is shared; changes go through your team repo first.
- Your **customizations** (your agency's style, your own stations, your process tweaks) belong in `/skills` and `/playbook`, not here.
