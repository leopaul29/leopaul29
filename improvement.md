# GitHub Repository Branding System

> A consistent branding system for all personal GitHub repositories, designed to make every project feel like it belongs to the same builder.

---

## At a glance

| Category         | ID      | Emoji | Accent |
| ---------------- | ------- | ----- | ------ |
| Hackathon        | HACK    | 🏆    | Orange |
| Open Source      | OSS     | 🌍    | Green  |
| SaaS Experiment  | SAAS    | 💼    | Blue   |
| AI Agent         | AGENT   | 🤖    | Purple |
| Chrome Extension | EXT     | 🧩    | Cyan   |
| Content Tool     | CONTENT | ✍️    | Pink   |
| Learning Project | LAB     | 🧪    | Yellow |

- **README spine:** `Title → Tagline → Overview → Problem → Solution → Features → Tech Stack → Roadmap`
- **About:** `[Emoji] Context/Event · Short Description · Date`
- **Naming:** 1–2 words · memorable · product-like · future-proof

**Portfolio mapping:** 🏆 *AI Bicycle* (Liquid AI, Tokyo) · 🤖 *Kizuna Link* (Impact Tokyo) · 🤖 *XRPL Oracle Omikuji* (Clawathon)

---

## 1. Goals

The repository branding system should:

- Standardize README titles.
- Standardize README introductions.
- Standardize GitHub About descriptions.
- Standardize repository cover images.
- Create a recognizable visual identity across projects.
- Provide reusable templates for future repositories.
- Make projects easy to understand for recruiters, developers, hackathon judges, collaborators, and future employers.
- Communicate a consistent identity as an AI-native, product-minded builder.

The overall objective is not only consistency, but recognition:

> Someone should be able to open several repositories and immediately feel that they were built by the same person.

---

## 2. Repository Categories

Every repository should belong to a clearly defined category.

| Category         | Identifier | Emoji |
| ---------------- | ---------- | ----- |
| Hackathon        | HACK       | 🏆    |
| Open Source      | OSS        | 🌍    |
| SaaS Experiment  | SAAS       | 💼    |
| AI Agent         | AGENT      | 🤖    |
| Chrome Extension | EXT        | 🧩    |
| Content Tool     | CONTENT    | ✍️    |
| Learning Project | LAB        | 🧪    |

The category can be reflected consistently across:

- README
- GitHub About section
- Cover image
- GitHub topics
- Repository metadata

The category system should remain simple and recognizable rather than becoming a complex taxonomy.

---

## 3. README Title Convention

### Recommended Format

```md
# Product Name

> One-line value proposition
```

### Example

```md
# Kizuna Link

> A voice-first AI companion connecting seniors to city-hall services and their family.
```

### Rationale

Keep the title itself clean and professional.

Avoid — casual, does not scale well across many repositories:

```md
# Product Name 🚀
```

Avoid — makes titles unnecessarily long and harder to scan:

```md
# Product Name | One-line value proposition
```

Instead, separate the product name from its value proposition:

```text
Product Name
↓
One-line value proposition
```

This creates a clean visual hierarchy and remains scalable as the portfolio grows.

---

## 4. Standard README Introduction

### Recommended Structure

```md
# Product Name

> One-line value proposition

## Overview
What the project is.

## Problem
What problem exists.

## Solution
How the project solves the problem.

## Key Features
- Feature
- Feature
- Feature

## Tech Stack
- Technology
- Technology
- Technology

## Use Cases
Who benefits from the project and how.

## Roadmap
Future plans and potential improvements.

## License
License information.
```

### Philosophy

The standard introduction should answer these questions in order:

1. **What is it?**
2. **What problem does it address?**
3. **How does it solve the problem?**
4. **What are the important features?**
5. **What technologies power it?**
6. **Where is it going next?**

This is preferable to a generic introduction because it communicates both product thinking and technical depth.

---

## 5. Hackathon README Structure

Hackathon repositories should emphasize the challenge, solution, demo, and context.

```md
# Product Name

> One-line value proposition

🏆 Hackathon Project
📍 Location
📅 Date

## Challenge
Description of the problem or challenge addressed.

## Solution
Description of the solution built.

## Demo
Link to the live demo, video, or presentation.

## Features
- Feature
- Feature
- Feature

## Tech Stack
- Technology
- Technology
- Technology

## Team
Contributors.

## Hackathon Details
- Hackathon:
- Location:
- Date:
```

The goal is to make the repository immediately understandable to hackathon judges, recruiters, future collaborators, and developers reviewing the project.

---

## 6. GitHub About Section

The GitHub About section should be:

- Short
- Professional
- Readable on mobile
- Immediately understandable
- Consistent across repositories

Keep it short enough to avoid aggressive truncation.

### Recommended Format

```text
[Category Emoji] Context/Event · Short Description · Date
```

### Hackathon Example

```text
🏆 Impact Tokyo · Voice-first wellness companion for seniors · Mar 2026
```

It communicates:

1. This is a hackathon project.
2. Where or in what context it was built.
3. What it does.
4. When it was built.

### Alternative: Category-First Format

```text
[HACK] Multi-agent startup validator · Tokyo · Jun 2026
```

- **Advantages:** highly structured, easy to scan, consistent with technical metadata.
- **Disadvantages:** less visually appealing, feels more like internal documentation.

### Alternative: Portfolio-Oriented Format

```text
Built during Tokyo AI Hackathon · Multi-agent startup validation platform
```

- **Advantages:** recruiter-friendly, provides context immediately.
- **Disadvantages:** less visually recognizable as a hackathon project, less consistent across many project categories.

### Non-Hackathon Examples

Adapt the same principle, dropping the event:

```text
💼 AI-powered startup research platform for founders
🌍 Open-source toolkit for autonomous AI workflows
🤖 Multi-agent framework for startup validation and market research
```

---

## 7. Repository Cover Image System

Every repository should have a generated cover image using the same visual system. The objective is a recognizable personal visual identity across the entire GitHub portfolio.

### Core Design Philosophy

The visual direction should feel modern, technical, minimal, developer-oriented, product-oriented, geometric, future-focused, and professional.

The aesthetic should be closer to modern developer and startup brands such as **Linear, Vercel, Stripe, and GitHub Next**.

Avoid: gaming-oriented visuals, Web3 aesthetics, neon cyberpunk, excessive 3D, generic AI imagery, and stock photography.

---

## 8. Visual Identity

### Core Visual Keywords

Minimal · Technical · Geometric · Gradient · Future-focused · Clean · Systematic

### Base Color Palette

Use dark graphite backgrounds as the common foundation:

```text
#0F172A
#111827
#18181B
```

The exact color can vary slightly between projects, but the overall visual language should remain consistent.

### Category Accent Colors

| Category         | Accent |
| ---------------- | ------ |
| Hackathon        | Orange |
| Open Source      | Green  |
| SaaS             | Blue   |
| AI Agent         | Purple |
| Chrome Extension | Cyan   |
| Content Tool     | Pink   |
| Learning Project | Yellow |

The category accent should be used for gradients, small visual highlights, category labels, and abstract graphics — it should not dominate the entire image.

---

## 9. Typography

Recommended typefaces: **Inter, Geist, IBM Plex Sans**.

The overall typography should be sans-serif, modern, clean, highly legible, and strong enough for large titles.

When generating images with AI, use the instruction `modern sans-serif typography`. For important project names, AI-generated typography can be unreliable — if possible, generate the visual without critical text and add the final text manually in a design tool.

---

## 10. Cover Image Composition

All repository covers should follow the same basic layout.

```text
+-------------------------------------------+
|                                           |
|  Product Name                             |
|  One-line description         Abstract    |
|  CATEGORY                     Technical   |
|                               Graphic     |
|                                           |
+-------------------------------------------+
```

### Left Side

- Project name (strongest visual element)
- Short tagline
- Optional category label

### Right Side

Use an abstract technical visual related to the project. Possible metaphors: network nodes, agent graphs, data flows, geometric structures, connected systems, workflow diagrams, abstract architecture, modular components.

Avoid literal screenshots unless there is a specific reason to include them.

### Avoid

People · stock photography · generic robot illustrations · busy dashboards · excessive text · UI screenshots · clutter · overly complex compositions.

---

## 11. Reusable Cover Image Prompt

Use the following prompt as the base template for generating repository covers.

```text
Create a GitHub repository cover image.

Project Name: {PROJECT_NAME}
Category: {CATEGORY}
Description: {DESCRIPTION}
Tech Stack: {TECH_STACK}

Visual Style:
Modern developer branding.
Dark graphite background.
Clean geometric composition.
Professional startup aesthetic.
Minimalistic design.
Subtle gradients.
High contrast.
Vector-style illustration.
Technical visual language.
Large typography on the left side.
Abstract system or technical illustration on the right side.
Category accent color: {CATEGORY_COLOR}.

The visual should communicate the project's concept without relying on literal screenshots.

No screenshots. No people. No stock photography. No clutter.
No excessive 3D. No cyberpunk aesthetic. No generic AI robot imagery.

Optimized for a GitHub repository social preview image.
Aspect ratio 1280x640.
```

---

## 12. Personal Naming Conventions

Project names should generally be one or two words, memorable, product-like, easy to pronounce and remember, and suitable for a future standalone product.

**Preferred style:**

```text
StartupScout · AgentForge · ResearchFlow · MarketPilot · IdeaLens · SignalStack · BuildLoop
```

**Avoid names that feel temporary or purely technical:**

```text
awesome-ai-agent-project · hackathon-submission-v3 · gpt-market-analysis-tool
```

The objective is to make even experimental projects feel like intentional products.

---

## 13. Repository Template: Hackathon

```md
# Product Name

> One-line value proposition

🏆 Hackathon Project · {Hackathon Name}
📍 {Location}
📅 {Date}

## Challenge
{What problem or challenge were you trying to solve?}

## Solution
{What did you build and how does it solve the problem?}

## Demo
{Link}

## Features
- {Feature}
- {Feature}
- {Feature}

## Tech Stack
- {Technology}
- {Technology}
- {Technology}

## Team
{Contributors}

## Hackathon Details
- Hackathon: {Name}
- Location: {Location}
- Date: {Date}
```

### Filled example — *Kizuna Link* (Impact Tokyo, Mar 2026)

```md
# Kizuna Link

> A voice-first AI companion connecting seniors to city-hall services and their family.

🏆 Hackathon Project · Impact Tokyo
📍 Tokyo, Japan
📅 Mar 2026

## Challenge
Seniors struggle to navigate *Kuyakusho* (ward office) services and to stay
connected with distant family, especially when apps assume comfort with screens.

## Solution
A voice-first AI bridge that turns spoken requests into the right city-hall
service and keeps family in the loop through familiar messaging.

## Demo
https://github.com/leopaul29/impacttokyo-07032026

## Features
- Voice-first interaction, no app learning curve
- Guided access to Kuyakusho services
- Family updates over LINE

## Tech Stack
- Next.js
- Tailwind CSS
- OpenAI API
- LINE Messaging API
- Simulated MyNumber logic

## Team
- [@leopaul29](https://github.com/leopaul29)

## Hackathon Details
- Hackathon: Impact Tokyo
- Location: Tokyo, Japan
- Date: Mar 2026
```

---

## 14. Repository Template: Open Source

```md
# Product Name

> Open-source tool for {purpose}

🌍 Open Source

## Overview
{What the project is.}

## Why
{Why the project exists.}

## Features
- {Feature}
- {Feature}
- {Feature}

## Getting Started
{Installation and usage instructions.}

## Contributing
{Contribution guidelines.}

## Tech Stack
- {Technology}
- {Technology}

## Roadmap
{Future plans.}

## License
{License}
```

---

## 15. Repository Template: SaaS

```md
# Product Name

> Helping {audience} achieve {outcome}

💼 SaaS Experiment

## Overview
{What the product is.}

## Problem
{What problem exists.}

## Solution
{How the product solves it.}

## Key Features
- {Feature}
- {Feature}
- {Feature}

## Demo
{Link}

## Tech Stack
- {Technology}
- {Technology}
- {Technology}

## Roadmap
{Future plans.}
```

---

## 16. Repository Template: AI Agent

```md
# Product Name

> Autonomous AI agents for {purpose}

🤖 AI Agent

## Overview
{What the agent or agent system does.}

## Problem
{What problem requires automation or intelligence?}

## Solution
{How the AI agent solves the problem.}

## Architecture
{Brief explanation of the agent architecture.}

## Features
- {Feature}
- {Feature}
- {Feature}

## Tech Stack
- {Technology}
- {Technology}
- {Technology}

## Example Workflow
{Describe or visualize a typical agent workflow.}

## Roadmap
{Future improvements.}
```

---

## 17. Personal Builder Brand

Every repository should communicate a consistent builder identity.

**Core brand attributes:** AI-native · Builder · Product-minded · Systems thinker · Rapid prototyper · Open-source friendly · Startup-oriented

The repository does not need to explicitly state these attributes. They should emerge naturally from:

- The projects selected
- The quality of documentation
- The visual consistency
- The technical depth
- The product framing
- The speed and variety of experimentation

---

## 18. Final Branding System

**README:**

```text
Product Name → One-line value proposition → Overview → Problem → Solution → Features → Tech Stack → Roadmap
```

**About:**

```text
[Category Emoji] Context/Event · Short Description · Date
```

Example: `🏆 Impact Tokyo · Voice-first wellness companion for seniors · Mar 2026`

**Cover:**

```text
Dark graphite background + Category accent color + Large project typography
+ Abstract technical visual + Consistent composition
```

**Naming:**

```text
1–2 words + Memorable + Product-like + Future-proof
```

### Overall Portfolio Impression

A recruiter or developer opening several repositories should immediately see consistent naming, consistent README structure, consistent visuals, clear project categories, strong product thinking, technical credibility, and a coherent personal builder identity.

The GitHub profile should feel less like a collection of random projects and more like a portfolio of experiments and products built by one consistent engineer.

---

## 19. Recommended Long-Term Principle

The branding system should be **consistent at the system level, but flexible at the project level**.

**Keep fixed:** README title hierarchy · introduction structure · About format · cover image dimensions · cover image composition · typography · base background · category system · naming philosophy.

**Allow to vary:** project-specific accent color · abstract illustration · project tagline · features · README sections · technical architecture.

The result should be:

> **Same builder. Different products.**
