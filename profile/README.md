# WetNote 🏆

**AI-assisted tools for underwater projects.**

WetNote builds practical tools for people working underwater. Our first
tool estimates the **typology of amphorae** from a single photo: upload an
image, and AI suggests which type it most likely is. The project began as
a master's thesis in **underwater archaeology** at Akdeniz University and
is growing into something broader.

🔗 [wetnote.com](https://wetnote.com)

## The long-term vision

WetNote is an **umbrella brand for underwater projects** — one brand, many
tools. Amphora typology is the start; the roadmap reaches into other
underwater work such as:

- 🏺 Amphora typology & classification *(first tool — in development)*
- 🎥 Cave-map dive video player *(planned)*
- 🕸️ Ghost-net detection & removal diving
- 📐 Photogrammetry & 3D reconstruction
- 🗺️ Underwater site mapping
- ⚓ Archaeology & survey tooling

The goal: a shared toolkit any underwater-project maker can use —
independent divers, universities, and diving communities alike. Free while
the research matures, with premium options considered later.

## How it's organised

WetNote is **multi-repo**: each tool and surface lives in its own
repository, and one repo — `core_docs` — is the single source of truth that
every other repo follows. Each repo is maintained by a dedicated AI agent
working under human approval, coordinating through the `communication` repo.

| Repo | Role |
|---|---|
| `core_docs` | Source of truth — standards, decisions, and rules every repo follows |
| `communication` | Cross-repo coordination and messaging |
| `www.wetnote.com` | Public landing page and web shell |
| `amphai` | The amphora-typology app (image → estimated type) |
| `wetnote-functions` | Shared backend (Cloud Functions) for all WetNote apps |
| `thesis-research` | The research trail behind AmphorAI — methodology, sources, provenance |
| `.github` | This organization profile |

*More repos join as the project grows.*

## Who's behind it

**Nevcan Uludaş** — founder, developer, and researcher. Master's candidate
in underwater archaeology at Akdeniz University, currently building WetNote
solo.

## Status

Early development & research — 2026.

- 🏺 **AmphorAI** — amphora typology app, in active development
- 🌐 **wetnote.com** — landing page & web shell, in progress
- 🎥 **caveline** — cave-map video player, planned (concept stage)

Watch this space. 🐚
