# Software Engineering Principles & Design — Obsidian Vault

**English** · [فارسی ↓](#-نسخه-فارسی)

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

The original notes, structure, configuration and templates in this repository are released under the [MIT License](LICENSE).

The license does **not** cover the Pressman figure images under `98_Assets/` (copyright of the publisher, included for personal study with citation) or the third-party plugin bundles under `.obsidian/plugins/`. See [NOTICE.md](NOTICE.md) for full attribution and scope.

---

<div dir="rtl">

## 🇮🇷 نسخه فارسی

یک **مخزن دانش (Vault) آمادهٔ آمستر برای Obsidian**، مربوط به درس **اصول طراحی و مهندسی نرمافزار**. این والت بر پایهٔ **جزوهٔ دستنویس کلاسی** و نمودارهای کتاب مرجع **مهندسی نرمافزار راجر پرسمن (ویرایش نهم)** ساخته و تکمیل شده است.

همهٔ یادداشتها **فارسی** هستند، ۳۷ تصویر نمودار بهصورت لوکال در پوشهٔ `98_Assets` ذخیره شدهاند (بنابراین والت کاملاً آفلاین کار میکند) و کل محتوا از طریق یک **نقشهٔ راه (MOC)** فصلفصل به هم لینک شده است.

### ✨ ویژگیها

- **ناوبری بر پایهٔ MOC** — یک یادداشت نقشهٔ راه که همهٔ مباحث را فصلبهفصل به هم وصل میکند.
- **انطباق فصلفصل با پرسمن** — در هر یادداشت، دقیقاً شمارهٔ شکل پرسمنِ استفادهشده ذکر شده است (مثلاً *شکل ۲-۳ آبشاری*، *شکل ۲-۵ مارپیچی*، *شکل ۱-۱ لایههای مهندسی نرمافزار*).
- **۳۷ نمودار** بهصورت لوکال در `98_Assets/` — رندر کامل بدون اینترنت.
- **جعبهابزار شب امتحان** — چکلیست نکات طلایی، جدول مقایسهٔ جامع مدلهای فرآیند و واژهنامهٔ تخصصی.
- **قالب یادداشت آماده** با YAML frontmatter (`course`، `chapter`، `status`، `tags`، `aliases`) و بلوکهای callout برای تعریف کلیدی و نکات امتحانی.
- **تنظیمات از پیش آمادهٔ Obsidian** — پشتیبانی راستبهچپ (RTL)، Dataview، Excalidraw، Spaced Repetition، Omnisearch و Style Settings.

### 📂 ساختار پوشهها

| پوشه | محتوا |
|---|---|
| `00_MOC` | 🗺️ نقشهٔ راه — از اینجا شروع کن |
| `01_SDLC` | چرخهٔ تولید نرمافزار، فعالیتهای چارچوبی، جریانهای فرآیندی و مدلهای فرآیند (آبشاری، افزایشی، نمونهسازی، مارپیچی) |
| `02_Agile` | فرآیند چابک، مانیفست، اسکرام، XP و مدلسازی چابک |
| `03_RUP` | فرآیند یکپارچهٔ منطقی، فازها و تکرارها |
| `04_Requirements` | مهندسی نیازمندیها، عملیاتی/غیرعملیاتی و مدیریت نیازمندی |
| `05_User-Stories` | داستان کاربر، 3Cs، معیارهای پذیرش و مقایسه با Use Case |
| `06_MVP` | حداقل محصول پذیرفتنی و چرخهٔ ساخت-اندازهگیری-یادگیری |
| `07_Exam-Prep` | 📊 جدول مقایسهٔ مدلها و ⚡ چکلیست نکات طلایی |
| `08_Glossary` | 📖 واژهنامهٔ تخصصی مهندسی نرمافزار |
| `09_Software-Design` | فرایند طراحی، مفاهیم و اصول، معماری و UML، طراحی مبتنی بر الگو |
| `10_Quality-and-Testing` | تضمین کیفیت، بررسی فنی، اصول آزمون، نگهداری و مهندسی مجدد |
| `98_Assets` | تصاویر نمودارها (PNG) |
| `99_Templates` | قالب یادداشت مفهومی |

### 🚀 شروع سریع

1. [Obsidian](https://obsidian.md) را نصب کن.
2. مخزن را clone کن:
   ```bash
   git clone https://github.com/ParsaPRF/Software-Engineering-Obsidian-Vault.git
   ```
3. در Obsidian گزینهٔ **Open folder as vault** را بزن و پوشهای را انتخاب کن که داخلش `.obsidian` قرار دارد.
4. فایل **`00_MOC/🗺️ نقشه راه اصول طراحی و مهندسی نرمافزار.md`** را باز کن و از نقشهٔ راه شروع کن.

> **نکتهٔ راستبهچپ:** چون یادداشتها فارسیاند، والت با پلاگین *Obsidian RTL* تنظیم شده است. اگر جهت متن درست نبود، از **Settings → Community plugins → RTL** جهت را روی *RTL* بگذار.

### 🧩 پلاگینها

باندل پلاگینها داخل `.obsidian/plugins` قرار دارد تا والت بلافاصله بعد از clone کار کند:
`dataview` · `obsidian-excalidraw-plugin` · `obsidian-spaced-repetition` · `omnisearch` · `obsidian-style-settings` · `obsidian-rtl` · `obsidian-hover-editor` · `obsidian-image-toolkit` · `obsidian-quiet-outline` · `obsidian-git` · `better-export-pdf`

> پلاگین **`remotely-save`** در مخزن قرار ندارد، چون باندل منتشرشدهٔ آن اعتبارنامههای OAuth گوگل نویسندهٔ اصلی را هاردکد دارد و GitHub Push Protection آن را رد میکند. اگر به همگامسازی ابری نیاز داری، از داخل خود Obsidian نصبش کن.

### 📝 قالب یادداشت

هر یادداشت با YAML frontmatter شروع میشود و این ساختار را دنبال میکند:
تعریف کلیدی (`> [!info]`) ← تشریح و جزئیات ← ارتباط با سایر مفاهیم با `[[wikilinks]]` ← نکات امتحانی (`> [!warning]`).
برای یادداشت جدید از `99_Templates/قالب یادداشت مفهومی درس.md` استفاده کن.

### 📚 منبع

- Roger S. Pressman, Bruce R. Maxim — *Software Engineering: A Practitioner's Approach*, 9th Edition
- جزوه و نمودارهای کلاسی

### 📄 مجوز

یادداشتها، ساختار و تنظیمات این مخزن تحت [مجوز MIT](LICENSE) منتشر شدهاند. تصاویر نمودارهای پرسمن در `98_Assets/` و باندل پلاگینهای شخص ثالث **تحت این مجوز نیستند** — جزئیات و فهرست منابع در فایل [NOTICE.md](NOTICE.md) آمده است.

</div>