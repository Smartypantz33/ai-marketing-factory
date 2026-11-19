# Outputs

Everything the factory produces lives here, in one folder per client. The work order is `calendar/content-calendar.csv`: one row per asset.

```
outputs/
└── rya-rightsizing/
    ├── strategy/            research-personas/, positioning-messaging/, marketing-plan/, content-calendar/
    ├── reports/             performance report, insights summary, next-cycle brief
    └── <Asset ID>/          one folder per calendar row, e.g. C1-A01/ or S1/
        ├── <Asset ID>-copy-v2.md        copy, caption, alt text, CTA
        ├── <Asset ID>-slide-1.png       one image per slide or frame
        └── <Asset ID>-sources.md        prompts, tools, image sources, Canva link
```

## Naming

- **Strategy and reports: date first.** `YYYY-MM-DD-<station>-<short-description>.md`, with `-v2`, `-v3` for revisions.
- **Assets: Asset ID first**, written exactly as it appears in your calendar. `<Asset ID>-<part>-vN.<ext>` for versioned files, `<Asset ID>-<part>.<ext>` for the rest.
- Lowercase, hyphens, no spaces (Asset IDs keep their capitals).
- Only the approved version goes here. Drafts stay in your personal repo.

## Video

MP4 files go in OneDrive: `Rya Video Assets – Fall 2026 / Group ## / <Asset ID>/`. The repo folder holds the script, captions, a thumbnail, `<Asset ID>-video-link.md` and `<Asset ID>-sources.md`.

## Status line

Every output starts with `DRAFT – awaiting review`, or `APPROVED – YYYY-MM-DD`.
