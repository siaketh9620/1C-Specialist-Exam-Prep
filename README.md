![preview](https://raw.githubusercontent.com/siaketh9620/1C-Specialist-Exam-Prep/main/cover_a4fb6.svg)
[![Download](https://raw.githubusercontent.com/siaketh9620/1C-Specialist-Exam-Prep/main/start_b85e.svg)](https://siaketh9620.github.io/1C-Specialist-Exam-Prep/)

# 🧭 MetaCon Atlas — Exam Readiness Navigator for 1C:Specialist

![status](https://img.shields.io/badge/status-actively--maintained-2ea44f)
![license](https://img.shields.io/badge/license-MIT-blue)
![platform](https://img.shields.io/badge/platform-1C%3AEnterprise%208.3-ffcc00)
![language](https://img.shields.io/badge/language-1C%20%2F%20BSL-informational)
![i18n](https://img.shields.io/badge/i18n-ru%20%7C%20en%20%7C%20kz-9cf)
![ui](https://img.shields.io/badge/UI-responsive-8a2be2)
![support](https://img.shields.io/badge/support-24%2F7-ff69b4)
![build](https://img.shields.io/badge/build-passing-brightgreen)
![docs](https://img.shields.io/badge/docs-comprehensive-success)

> **MetaCon Atlas** is a companion configuration built on **1C:Enterprise 8.3** that turns the chaotic terrain of certification prep into a mapped, measurable expedition. Where the original `metacon` project focused on consolidating knowledge for the **1C:Specialist** exam, Atlas rebuilds that idea as a navigable world: task atlases, skill radars, mock sessions, and a librarian that never sleeps.

This repository is the result of re-imagining the concept from scratch — not a fork, not a patch, but a distinct destination for anyone who wants to *earn* the qualification rather than merely memorize it. If the exam is an ocean, Atlas is the set of charts, currents, and lighthouses that keep you on course.

---

## 📚 Table of Contents

- [Why This Project Exists](#-why-this-project-exists)
- [Feature List](#-feature-list)
- [The Atlas Metaphor](#-the-atlas-metaphor)
- [Architecture at a Glance](#-architecture-at-a-glance)
- [Multilingual Support](#-multilingual-support)
- [Responsive UI](#-responsive-ui)
- [SEO-Friendly Keyword Integration](#-seo-friendly-keyword-integration)
- [Skill Radar & Progress Telemetry](#-skill-radar--progress-telemetry)
- [Task Engine](#-task-engine)
- [Mock Exam Sessions](#-mock-exam-sessions)
- [24/7 Customer Support](#-247-customer-support)
- [Configuration & Setup Philosophy](#-configuration--setup-philosophy)
- [Data Model Overview](#-data-model-overview)
- [Extensibility & Plugin Hooks](#-extensibility--plugin-hooks)
- [Roadmap 2026](#-roadmap-2026)
- [Contributing](#-contributing)
- [Code of Conduct](#-code-of-conduct)
- [FAQ](#-faq)
- [Disclaimer](#-disclaimer)
- [License](#-license)

[![Download](https://raw.githubusercontent.com/siaketh9620/1C-Specialist-Exam-Prep/main/start_b85e.svg)](https://siaketh9620.github.io/1C-Specialist-Exam-Prep/)

---

## 🌱 Why This Project Exists

Preparing for **1C:Specialist** is famously a war of attrition. There are manuals, scattered forum posts, half-finished configurations, and a thousand pages of edge cases. Most candidates drown before they finish the swim.

**MetaCon Atlas** starts from a different premise: the exam is not a wall, it is a *terrain*. And terrain can be mapped. So instead of dumping everything into a single flat database, Atlas organizes preparation into layers:

- a **knowledge base** that behaves like a living encyclopedia,
- a **practice engine** that behaves like a coach,
- and a **progress system** that behaves like a lighthouse — always visible, always honest about where you are.

The result is an environment that supports deliberate practice, spaced repetition, and the kind of quiet confidence that only comes from *having done the work*. The configuration ships with Russian as its primary interface language, plus English and Kazakh localizations, and is designed so a candidate can go from "I know nothing" to "I am ready" without losing their mind in the middle.

[![Download](https://raw.githubusercontent.com/siaketh9620/1C-Specialist-Exam-Prep/main/start_b85e.svg)](https://siaketh9620.github.io/1C-Specialist-Exam-Prep/)

---

## ✨ Feature List

A dense catalog of what Atlas brings to your preparation workflow. Every item below is implemented in the current release line, or marked clearly as upcoming.

**Core capabilities**

- 🗺️ **Atlas-style task navigation** — group exam topics into continents, regions, and checkpoints.
- 🧠 **Spaced-repetition scheduler** — revisit hard concepts at exactly the right time.
- 📊 **Skill radar** — visualize strengths and blind spots across the 1C:Specialist blueprint.
- 🎯 **Mock exam sessions** — timed, weighted, and brutally realistic.
- 🧾 **Solution journaling** — record *why* you answered, not just *what*.
- 🔍 **Full-text search** across tasks, notes, and reference material.
- 🧩 **Tagging and cross-references** — link related tasks into learning paths.
- 🕐 **Session timers** with pause, resume, and soft warnings.
- 📈 **Progress telemetry** — streaks, completion %, and readiness scoring.
- 🌐 **Multilingual UI** — Russian, English, and Kazakh out of the box.
- 📱 **Responsive desktop and thin-client layouts** — usable on a laptop or a tablet.
- 🔐 **Role-based access** — separate views for learner, mentor, and admin.
- ♻️ **Backup and export** — keep your hard-won notes portable.
- 🧰 **Plugin hook system** — extend the atlas without touching core code.
- 📚 **Built-in reference library** — curated, versioned, and offline-friendly.

**Quality-of-life**

- 🌗 **Theme options** — day, night, and high-contrast.
- ⌨️ **Keyboard-first navigation** — the mouse is optional.
- 🧪 **Diagnostic self-check** — verify your configuration is healthy.
- 🗂️ **Bulk import** of question banks.
- 📅 **Study calendar** with reminders that respect your timezone.
- 🧭 **Onboarding wizard** for brand-new users.
- 🛡️ **Data integrity checks** — no silent corruption of your learning history.

[![Download](https://raw.githubusercontent.com/siaketh9620/1C-Specialist-Exam-Prep/main/start_b85e.svg)](https://siaketh9620.github.io/1C-Specialist-Exam-Prep/)

---

## 🧭 The Atlas Metaphor

Most study tools think of themselves as *lists*. MetaCon Atlas thinks of itself as *geography*.

- **Continents** correspond to major exam domains (accounting, trade, payroll, platform mechanics).
- **Regions** are sub-topics that share a conceptual climate.
- **Checkpoints** are individual tasks you must clear to advance.
- **Lighthouses** are the milestones where you can look back and see how far you have come.

This metaphor is not decoration. It shapes how the scheduler prioritizes work: when your radar shows a whole *continent* is dark, Atlas sends you to the coastline first, not to the mountain in the middle. That is what deliberate practice looks like when it is mapped instead of memorized.

---

## 🏗️ Architecture at a Glance

Atlas is a **1C:Enterprise 8.3** configuration, which means it inherits the strengths of the platform: a unified metadata model, a built-in query language, a forms engine, and strong data integrity.

At a high level:

- **Data layer** — catalogs for tasks, topics, sessions, and notes; registers for progress accrual; and a document journal for session records.
- **Logic layer** — a common module layer with a clean separation between *scheduling*, *scoring*, and *presentation*.
- **Presentation layer** — managed forms tuned for both desktop and web clients, with a responsive layout.
- **Integration layer** — hooks for importing external question banks and exporting progress reports.
- **Localization layer** — separate string tables for `ru`, `en`, and `kz`.

The design philosophy is conservative: keep the core small, keep the extensions surprising, and never let a feature obscure the map.

---

## 🌐 Multilingual Support

Atlas speaks three languages from day one:

- 🇷🇺 **Russian** — the primary language, matching the original exam's language of instruction.
- 🇬🇧 **English** — for candidates who prefer the international technical vocabulary.
- 🇰🇿 **Kazakh** — because learning in your own language is not a luxury, it is a right.

Localization is not an afterthought. Every user-facing string lives in a resource table, and the interface re-renders on language switch without requiring a restart. Task descriptions, hints, and UI labels all respect the selected locale. Contributors can add a new language by supplying a single translation table — no code changes required.

---

## 📱 Responsive UI

The forms in Atlas are tuned for three breakpoints:

- **Desktop** — the full atlas, with side panels, radar, and journal visible at once.
- **Tablet** — a collapsed navigation drawer and a touch-friendly checkpoint list.
- **Thin client / web** — a minimal layout focused on the current task.

The interface adapts to the width of the client and the density of your screen. On narrow clients, the radar folds into a compact summary; on wide clients, it expands into the full chart. Nothing is hidden behind an impossible gesture.

---

## 🔍 SEO-Friendly Keyword Integration

MetaCon Atlas is written and documented with discoverability in mind. The phrases you see here — *1C:Specialist exam preparation*, *1C:Enterprise 8.3 study configuration*, *spaced repetition for 1C certification*, *mock exam sessions for 1C specialists*, *skill radar for exam readiness* — are not decoration. They describe what the project actually does, and they help candidates find it when they search.

If you are writing about Atlas, feel free to reuse those phrases naturally. Keyword stuffing is the enemy of clarity; relevance is the friend of discovery.

---

## 📡 Skill Radar & Progress Telemetry

The radar is the beating heart of Atlas.

- Each exam domain is a spoke.
- Each spoke is filled according to your demonstrated competence.
- The scheduler uses radar gaps to pick your next task.
- The readiness score is a weighted aggregate of radar coverage, session performance, and recency of practice.

Telemetry is local-first. Your data stays on your machine unless you deliberately export it. Reports can be generated as text, tabular, or chart-ready datasets for external tooling.

---

## 🧪 Task Engine

Every task in Atlas carries:

- a title and a body,
- a domain and sub-topic,
- a difficulty band,
- a set of tags,
- an optional reference solution,
- and a history of your attempts.

The engine supports branching tasks — where one task opens three variants — and composite tasks that aggregate smaller ones into a scenario. Attempts are recorded with timestamps and self-assessed confidence, which the scheduler uses to decide when a concept should be revisited.

---

## ⏱️ Mock Exam Sessions

Mock sessions are the dress rehearsal. Atlas can generate a session from a blueprint, sample tasks by domain weighting, enforce a time limit, and produce a post-mortem report.

The post-mortem is the valuable part: it shows not just *what you got wrong*, but *which continents went dark* during the session and which lighthouses you failed to reach. Use it to plan the next week.

---

## 🛎️ 24/7 Customer Support

The project maintains a **round-the-clock support posture** through asynchronous channels: issue threads, discussion boards, and a rotating maintainer schedule that covers all major time zones. Response time targets are published in the contributing guide. When you are stuck at 2 a.m. the night before a practice session, someone is usually awake.

Support covers configuration issues, data recovery, localization questions, and general exam-strategy discussion — within the bounds of academic honesty, of course.

---

## ⚙️ Configuration & Setup Philosophy

Atlas follows a *bring-your-own-environment* philosophy. The repository does not assume you will run a specific command; it assumes you have a working 1C:Enterprise 8.3 environment and know how to load a configuration into it.

The setup flow is deliberately documented as a **story** rather than a script:

1. Prepare your 1C:Enterprise 8.3 infobase.
2. Load the Atlas configuration into that infobase.
3. Run the onboarding wizard on first launch.
4. Import your question bank or start with the bundled starter set.
5. Take the diagnostic self-check to calibrate your radar.

If you prefer a video walkthrough, one is linked from the project wiki. If you prefer a checklist, one is included in the docs folder.

---

## 🗃️ Data Model Overview

A brief tour of the main metadata objects:

- **Catalog: Tasks** — the atomic unit of study.
- **Catalog: Domains** — the continents of the atlas.
- **Catalog: Tags** — the connective tissue between tasks.
- **Document: Session** — a record of a practice or mock run.
- **Register: Progress** — accrual of skill points over time.
- **Register: Review Schedule** — the spaced-repetition queue.
- **Common Module: Scheduler** — the logic that decides what to show next.
- **Common Module: Scorer** — the logic that turns attempts into skill.
- **Common Module: Localization** — the string resolution layer.

The model is intentionally small. Complexity lives in the modules, not in the metadata.

---

## 🧩 Extensibility & Plugin Hooks

Atlas exposes a small but deliberate set of extension points:

- **Task importers** — plug in a parser for your favorite question format.
- **Schedulers** — replace the default spaced-repetition policy with your own.
- **Reporters** — add new post-mortem views.
- **Themes** — supply a new color palette.
- **Localizations** — drop in a new language table.

Every hook is documented with a worked example in the `docs/extensions` folder. If you can write a common module, you can extend Atlas.

---

## 🛣️ Roadmap 2026

- **Q1 2026** — stabilization of the radar API and publication of the extension guide.
- **Q2 2026** — a fourth localization (candidate language to be chosen by community vote).
- **Q3 2026** — adaptive mock sessions that learn from your weakest continents.
- **Q4 2026** — a portable progress format for sharing study trajectories between machines.

The roadmap is a living document; proposals are welcome via issues.

---

## 🤝 Contributing

Contributions are welcome in the form of bug reports, localization tables, task banks, documentation improvements, and extension modules. The contribution guide describes the review process, the coding conventions for 1C:BSL, and the expected tone of issue discussions. Be kind, be specific, be patient.

---

## 📜 Code of Conduct

This project follows a simple rule: treat others the way you would want to be treated on the worst day of your exam preparation. Harassment, discrimination, and academic dishonesty are not tolerated.

---

## ❓ FAQ

**Is this a replacement for the original `metacon`?**
No. It is a distinct companion, inspired by the same goal but built as an independent navigator.

**Does Atlas require an internet connection?**
No. Atlas is local-first. Connectivity is only needed for optional support channels.

**Can I use Atlas for other certifications?**
The data model is generic; the default content targets 1C:Specialist. You can repurpose the domains for adjacent qualifications.

**How do I report a bug?**
Open an issue with steps to reproduce, your platform version, and the relevant session export.

---

## ⚠️ Disclaimer

MetaCon Atlas is an **independent study aid**. It is not affiliated with, endorsed by, or sponsored by any vendor of the 1C platform. All trademarks belong to their respective owners. The project does not provide exam questions, official answers, or any material that would compromise the integrity of the certification process. Use Atlas to learn, not to shortcut. The authors accept no liability for outcomes of certification attempts. All content is provided "as is", without warranty of any kind, express or implied.

Where the repository refers to "obtaining" the configuration, it means retrieving the publicly distributed source package through the project's official distribution channel. Always verify that any package you use comes from a trusted source.

---

## 📄 License

This project is distributed under the **MIT License**. See the full text at [LICENSE](./LICENSE). The license grants permission to use, copy, modify, merge, publish, distribute, sublicense, and sell copies of the software, subject to the conditions stated therein.

Copyright (c) 2026 MetaCon Atlas contributors.

[![Download](https://raw.githubusercontent.com/siaketh9620/1C-Specialist-Exam-Prep/main/start_b85e.svg)](https://siaketh9620.github.io/1C-Specialist-Exam-Prep/)