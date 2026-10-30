# Outputs

Everything the factory produces lives here, one folder per client.

```
outputs/
└── rya-rightsizing/
    ├── 2026-11-05-research-personas.md
    ├── 2026-11-12-positioning-messaging.md
    ├── 2026-11-12-content-calendar-december.md
    └── 2026-11-19-social-week-1.md
```

## Naming

`YYYY-MM-DD-<station>-<short-description>.md`

- Lowercase, hyphens, no spaces.
- Never overwrite. A revision gets `-v2`, `-v3`.
- Images, video and other files from external tools go in the same client folder with the same date-first naming.

## Status line

The top of every output says its status:
- `DRAFT – awaiting review`
- `APPROVED – YYYY-MM-DD`

## Commit messages

Describe the work, e.g. `Add Rya social week 1 (approved)` or `Revise positioning v2 after client feedback`. Your commit history is your proof of work.
