# Shukinkara

主金空 - sovereign wealth vessel.

A member-owned cooperative grounded in fourteen articles, with Hivemind.AI-OS as the personal AI gateway each member receives.

Authored by Cameron Moir, Brisbane, 2026.

## What is this repo

The complete Shukinkara document set, hosted as a static site. Includes the canonical constitution, all version history, fifty-plus source documents from years of UMB and Hivemind work, and three new content appendices (glossary, voting records, changelog).

## Structure

```
.
├── index.html                          Landing page (homepage)
├── shukinkara.html                     Same landing page, alternate URL
├── shukinkara-document-v8-1.html       Canonical constitution (current)
├── shukinkara-document-v6-2.html       Earlier major revision
├── shukinkara-document-v4.html         Earlier draft
├── shukinkara-document-v3.html         Earlier draft
├── shukinkara-document-v2.html         Earlier draft
├── shukinkara-document.html            Original v1
└── appendices/
    ├── umb/                            UMB framework documents (18 files)
    ├── worldviews/                     The 117 mapping (3 files)
    ├── hivemind/                       Hivemind whitepapers and vision (6 files)
    ├── articles/                       Streamables.live article series (17 files)
    ├── master-plans/                   Project context master plans (4 files)
    ├── analysis/                       Standalone analysis docs (1 file)
    └── new/                            Glossary, Voting Records, Changelog (3 files)
```

## Reading the constitution

The current canonical version is `shukinkara-document-v8-1.html`. Open it in a browser. It includes:

- Collapsible Table of Contents at the top
- Section anchor IDs on every heading (`#some-section`)
- § permalink markers on hover
- Comprehensive Appendices section linking every source document
- Appendix sub-navigation for jumping between categories

Earlier versions are kept for the historical record. The Changelog appendix (`appendices/new/changelog.html`) summarises what changed between each version and why.

## Hosting

This is a static site. Any static host works:

- **GitHub Pages** - enable in repo settings, point to `main` branch, root folder
- **Vercel** - import the repo, no build step needed, deploys on push
- **Cloudflare Pages** - same pattern
- **Netlify** - same pattern
- **Self-hosted** - serve the directory with any web server (nginx, caddy, apache)

The only requirements: relative links work, `.html` files are served as `text/html`, `.md` files are served as `text/plain` or `text/markdown`. PDFs in the appendices folder open in the browser's native viewer.

## Versions

| File | Status | Notes |
|------|--------|-------|
| `shukinkara-document-v8-1.html` | **Canonical** | Current. Founder allocation added. |
| `shukinkara-document-v6-2.html` | Archive | Last v6 revision before v7 restructure. |
| `shukinkara-document-v4.html` | Archive | Six-section v4 expansion with Technical Reality, Governance of the Designers, Adversarial Scale. |
| `shukinkara-document-v3.html` | Archive | Restructure adding Bill of Digital Rights and What This Is Not. |
| `shukinkara-document-v2.html` | Archive | Personal AI gateway framing introduced. |
| `shukinkara-document.html` | Archive | Original v1. Soul Token / Covenant / Commandments language. |

## Licence

This document is released without restriction. Copy it, translate it, build from it. The only condition is that you do not lie about what it is.

## Contact

Cameron Moir - Brisbane, Australia.

[streamables.live](https://streamables.live)
