# Software Engineering Principles & Design — Obsidian Vault

A complete, exam-ready **Obsidian knowledge base** for a *Software Engineering Principles & Design* course, built from handwritten class notes and aligned chapter-by-chapter with **Roger S. Pressman, _Software Engineering: A Practitioner's Approach_ (9th Edition)**.

The notes are written in **Persian (فارسی)** and use a clean folder-based structure, a Map of Content (MOC) hub, an exam-prep section, a bilingual glossary, and a reusable note template. All diagrams are bundled locally as PNG assets, so the vault renders offline with no external dependencies.

---

## ✨ Features

- **MOC-driven navigation** — a single roadmap note links to every topic, chapter by chapter.
- **Chapter-by-chapter Pressman alignment** — each note cites the exact Pressman figure it embeds (e.g. *Fig. 2-3 Waterfall*, *Fig. 2-5 Spiral*, *Fig. 1-1 SE Layers*).
- **37 hand-picked figures** embedded locally under `98_Assets/` — everything renders offline.
- **Exam-prep toolkit** — a golden-rules checklist, a comprehensive process-model comparison table, and a technical glossary.
- **Reusable template** with YAML frontmatter (`course`, `chapter`, `status`, `tags`, `aliases`) and callout blocks for definitions and exam tips.
- **Pre-configured Obsidian setup** — RTL support, Dataview, Excalidraw, Spaced Repetition, Omnisearch, Style Settings, and more (see `.obsidian/`).

---

## 📂 Vault Structure

```
.
├── .obsidian/                        # Obsidian configuration and community plugins
└── Software-Engineering-Vault/       # The notes themselves
    ├── 00_MOC/                       # 🗺️ Map of Content — start here
    ├── 01_SDLC/                      # Software life cycle, framework activities, process flows, process models
    │   └── مدل‌های فرآیند/            # Waterfall · Incremental · Prototyping · Spiral
    ├── 02_Agile/                     # Agile process, manifesto, Scrum, XP, Agile Modeling
    ├── 03_RUP/                       # Rational Unified Process, phases and iterations
    ├── 04_Requirements/              # Requirements engineering, functional/non-functional, management
    ├── 05_User-Stories/              # User stories, 3Cs, acceptance criteria, Story vs. Use Case
    ├── 06_MVP/                       # MVP and Build-Measure-Learn / Go-No-Go
    ├── 07_Exam-Prep/                 # 📊 Comparison table, ⚡ golden-rules checklist
    ├── 08_Glossary/                  # 📖 Technical glossary
    ├── 09_Software-Design/           # Design process, concepts & principles, architecture/UML, patterns
    ├── 10_Quality-and-Testing/       # QA, technical review, testing principles, maintenance, reengineering
    ├── 98_Assets/                    # Figure images (PNG)
    └── 99_Templates/                 # Note template
```

---

## 📖 Contents Overview

| # | Topic | Highlights |
|---|-------|------------|
| 1 | **SDLC & Process Models** | SE layers, five framework activities, four process flows, umbrella activities, Polya's 4 steps, Hooker's principles, Waterfall / Incremental / Prototyping / Spiral |
| 2 | **Agile** | Cost of change, Agile Manifesto (4 values, 5 principles, 12 declarations), Scrum events & roles, XP framework activities, CRC cards, spikes, Agile Modeling |
| 3 | **RUP** | Two-dimensional process view, four phases and iterations, discipline workflows |
| 4 | **Requirements** | Seven requirements engineering tasks, functional vs. non-functional requirements, impact analysis, traceability matrix |
| 5 | **User Stories** | Story template, 3Cs (Card / Conversation / Confirmation), acceptance criteria, Story vs. Use Case |
| 6 | **MVP** | Minimum Viable Product, prototype stabilization, BML loop, Go/No-Go gate |
| 7 | **Software Design** | Design process and information flow, nine core design concepts, cohesion & coupling, architectural design, UML deployment diagrams, Buschmann & Henney principles, pattern-based design |
| 8 | **Quality & Testing** | SQA, technical reviews, testing principles, testing steps, maintenance types, ripple effect, reverse engineering, reengineering |
| 9 | **Exam Prep** | Comparison matrix of all process models, golden-rule checklist, technical glossary |

---

## 🚀 Getting Started

1. Install [Obsidian](https://obsidian.md).
2. Clone this repository:
   ```bash
   git clone https://github.com/ParsaPRF/Software-Engineering-Obsidian-Vault.git
   ```
3. In Obsidian, choose **Open folder as vault** and select the folder containing `.obsidian/`.
4. Open **`00_MOC/🗺️ نقشه راه اصول طراحی و مهندسی نرم‌افزار.md`** and start from the roadmap.

> **Note on RTL:** The notes are Persian, so the vault is pre-configured with the *Obsidian RTL* plugin. If text direction looks wrong, enable **Settings → Community plugins → RTL** and set direction to *RTL*.

---

## 🧩 Bundled Community Plugins

`.obsidian/plugins` ships with the plugin bundles so the vault works immediately after cloning:

`dataview` · `obsidian-excalidraw-plugin` · `obsidian-spaced-repetition` · `omnisearch` · `obsidian-style-settings` · `obsidian-rtl` · `obsidian-hover-editor` · `obsidian-image-toolkit` · `obsidian-quiet-outline` · `obsidian-git` · `better-export-pdf`

These plugins are the property of their respective authors and remain under their own licenses.

> **Not included: `remotely-save`.** Its published bundle embeds upstream Google OAuth credentials, which GitHub push protection rejects. Install it yourself from the plugin browser if you need cloud sync: [remotely-save](https://github.com/remotely-save/remotely-save).

---

## 📝 Note Conventions

Every note starts with YAML frontmatter and follows a consistent skeleton:

```yaml
---
course: اصول طراحی و مهندسی نرم‌افزار
chapter:
status: #مرور-نشده
tags: [software-engineering]
aliases: []
---
```

Then: a key-definition callout (`> [!info]`) → detailed explanation → relations to other concepts via `[[wikilinks]]` → exam tips callout (`> [!warning]`). Use `99_Templates/قالب یادداشت مفهومی درس.md` as the starting point for new notes.

---

## 📚 Reference

- Roger S. Pressman, Bruce R. Maxim — *Software Engineering: A Practitioner's Approach*, 9th Edition
- Course lecture notes (handwritten) and the figures embedded alongside them

---

## 📄 License

Notes, summaries and the vault structure are shared for study purposes. Pressman figure references are cited for academic attribution; plugin code belongs to its respective authors.