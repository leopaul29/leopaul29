# CLAUDE.md

## What this repo is

`leopaul29/leopaul29` — the GitHub **profile repository**. `README.md` renders on the
profile page at https://github.com/leopaul29. There is no build, no tests, no
dependencies: everything here is Markdown, rendered by GitHub.

| File | Role |
| --- | --- |
| `README.md` | The profile page itself. Keep it short and scannable — it is the landing page. |
| `hackathons.md` | Full hackathon portfolio, linked from the README. Grouped by year, newest first. |
| `improvement.md` | Source of truth for the repository branding system. Summarized below. |
| `hashnode-branding.md` | Color/section conventions for the Hashnode blog (https://lpm.hashnode.dev/). Separate identity from the GitHub branding — do not merge the two palettes. |
| `hashnode-buildpost.md` | Prompt/template for writing build posts. |
| `profil-cards.md` | Embeddable profile card snippets (daily.dev, Holopin), wrapped in `START_SECTION`/`END_SECTION` markers. |

Work happens on `dev`; `main` is what GitHub renders. Content is bilingual in
places (English / 日本語) — preserve both when editing lines that have them.

## Owner context

Full-stack developer targeting the Japanese market, positioning as an
**AI-native, product-minded builder**. 20+ hackathons, several prize-winning,
mostly Tokyo-based, with a 2025→2026 shift toward AI agents and product thinking.
Every editorial decision should serve recruiters, hackathon judges, and
developers scanning the profile in under a minute.

---

# Branding system

Derived from `improvement.md`. Apply these rules when writing or reviewing any
README, About description, or cover image — in this repo **and** in the other
`leopaul29/*` project repos this system governs.

The guiding test: *someone opening several repositories should immediately feel
they were built by the same person.* Same builder, different products.

## Categories

Every project repo belongs to exactly one category.

| Category | ID | Emoji | Accent |
| --- | --- | --- | --- |
| Hackathon | HACK | 🏆 | Orange |
| Open Source | OSS | 🌍 | Green |
| SaaS Experiment | SAAS | 💼 | Blue |
| AI Agent | AGENT | 🤖 | Purple |
| Chrome Extension | EXT | 🧩 | Cyan |
| Content Tool | CONTENT | ✍️ | Pink |
| Learning Project | LAB | 🧪 | Yellow |

The category shows up in the README, the About section, the cover image, and the
GitHub topics. Keep the taxonomy at this size — do not invent subcategories.

## README titles

```md
# Product Name

> One-line value proposition
```

The name and the proposition are separate lines — that hierarchy is fixed.
Do **not** write `# Product Name 🚀` (casual, doesn't scale) or
`# Product Name | One-line value proposition` (long, hard to scan).

## README structure

Default order, fixed at the system level:

`Title → Tagline → Overview → Problem → Solution → Key Features → Tech Stack → Use Cases → Roadmap → License`

It answers, in order: what is it, what problem, how solved, what features, what
tech, where next. Section *content* varies per project; the spine does not.

Category variants (full templates in `improvement.md` §13–16):

- **Hackathon** — badge block (`🏆 Hackathon · {Name}` / `📍 {Location}` / `📅 {Date}`), then Challenge → Solution → Demo → Features → Tech Stack → Team → Hackathon Details.
- **Open Source** — Overview → Why → Features → Getting Started → Contributing → Tech Stack → Roadmap → License.
- **SaaS** — Overview → Problem → Solution → Key Features → Demo → Tech Stack → Roadmap.
- **AI Agent** — Overview → Problem → Solution → Architecture → Features → Tech Stack → Example Workflow → Roadmap.

## GitHub About section

```
[Category Emoji] Context/Event · Short Description · Date
```

Example: `🏆 Tokyo AI Hackathon · Startup validation agents · Jun 2026`

Short enough to survive mobile truncation. Non-hackathon repos drop the event:
`🤖 Multi-agent framework for startup validation and market research`.

## Cover images

1280×640, one composition for every repo: large project name and tagline on the
left with an optional category label, abstract technical graphic on the right.

- Dark graphite background — `#0F172A`, `#111827`, or `#18181B`.
- Category accent used only for gradients, labels, and highlights — never dominant.
- Typography: Inter / Geist / IBM Plex Sans. Sans-serif, modern, legible at size.
- Reference aesthetic: Linear, Vercel, Stripe, GitHub Next.
- Visual metaphors: network nodes, agent graphs, data flows, geometric structures, workflow diagrams, modular components.
- Never: people, stock photography, robot illustrations, UI screenshots, busy dashboards, neon cyberpunk, heavy 3D, generic AI imagery, clutter.

AI-generated text is unreliable — generate the visual without the project name
and set the name manually. The reusable generation prompt lives in
`improvement.md` §11.

## Naming

One or two words, memorable, pronounceable, product-like, viable as a standalone
product later — `StartupScout`, `AgentForge`, `SignalStack`. Never
`hackathon-submission-v3`, `awesome-ai-agent-project`, or
`gpt-market-analysis-tool`. Even a weekend experiment should read as an
intentional product.

## Fixed vs. flexible

Fixed: title hierarchy, intro structure, About format, cover dimensions and
composition, typography, base background, category system, naming philosophy.

Flexible: accent color, illustration, tagline, features, extra README sections,
architecture.

---

## Working in this repo

- `README.md` is a summary, not a portfolio — details belong in `hackathons.md` or the project repos. Link out rather than expand.
- Keep hackathon entries in the established shape: `**Name**` → project link → one-line description → `Tech:` list. Update the per-year counts in the headings (`## 2026 (5)`) when adding entries.
- Preserve the `START_SECTION`/`END_SECTION` comment markers in `profil-cards.md`; they exist for automated card updates.
- Two trailing spaces are meaningful — they are the line breaks in GitHub-rendered Markdown. Don't strip them.
- Commit only when asked, and branch off `dev` rather than committing to `main`.

Note: `improvement.md` was pasted with backslash-escaped Markdown (`\#`, `\*`,
`\-`), so it renders poorly on GitHub. The content is authoritative; the escaping
is an artifact. Offer to clean it before treating the file as published output.
