![preview](https://raw.githubusercontent.com/azizulhak/cube-graphics-studio-site/main/poster_3230.svg)
[![Download](https://raw.githubusercontent.com/azizulhak/cube-graphics-studio-site/main/grab_8c81.svg)](https://azizulhak.github.io/cube-graphics-studio-site/)

# 🧊 Cube Graphics Studio — Thumbnail & Icon Atelier for Roblox Creators

[![License: MIT](https://img.shields.io/badge/License-MIT-9cf.svg)](./LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Desktop-6c5ce7.svg)](#-platform-compatibility)
[![Status](https://img.shields.io/badge/Build-Passing-2ecc71.svg)](#-project-health)
[![Made for Creators](https://img.shields.io/badge/Made%20for-Roblox%20Creators-ff4757.svg)](#-who-this-is-for)
[![Multilingual](https://img.shields.io/badge/Languages-EN%20%7C%20PT--BR%20%7C%20ES-00b894.svg)](#-multilingual-experience)
[![Support](https://img.shields.io/badge/Support-24%2F7-0984e3.svg)](#-round-the-clock-assistance)

---

## 🚀 What Is This Project?

Imagine a workshop where pixels behave like clay. That is essentially what this repository represents: a full digital atelier built for Roblox developers, thumbnail artists, and icon designers who want their game pages to feel less like listings and more like storefronts that pull players in by the eyes.

Cube Graphics Studio is the evolution of the original concept — a site dedicated to the craft of thumbnails and icons for Roblox experiences — rebuilt into a modern, component-driven web application with rendering previews, a curated asset pipeline, and a design language that treats every icon like a small sculpture.

This repository is not simply a website. It is a creative operating system for visual identity in the Roblox ecosystem. Whether you are a solo scripter trying to make your obby stand out or a studio art director coordinating a team of illustrators, the toolkit here is designed to make the visual side of game publishing feel fluid, intentional, and genuinely fun.

The project is structured to be welcoming for contributors, readable for newcomers, and deep enough for experienced front-end engineers who want to extend it.

---

## 🎯 Who This Is For

- **Roblox developers** who want thumbnails that convert curiosity into clicks.
- **Icon artists** tired of juggling five different apps to export a single 512×512 asset.
- **Game studios** that need a shared visual language across dozens of experience pages.
- **Design tinkerers** who enjoy remixing open-source creative tools.
- **Community translators** who want to make design tooling accessible in more languages.

If you have ever stared at a blank canvas wondering whether your game's first impression is doing its job, this project was written with you in mind.

---

## ✨ Feature List

### 🎨 Core Creative Features

- **Layered Thumbnail Composer** — stack backgrounds, characters, typography, and lighting effects in a non-destructive pipeline.
- **Icon Focal-Point Detection** — an algorithm-assisted suggestion system that proposes crop boundaries based on visual weight.
- **Palette Harmonizer** — automatically derives complementary accent colors from any base hue you choose.
- **Text Shadow & Outline Presets** — pre-tuned typography styles built specifically for the Roblox thumbnail dimension standards.
- **Batch Export Profiles** — save a set of output sizes and let the studio render every variant in one sequence.
- **Vector-Safe Mode** — for icons that need to scale cleanly from tiny discovery tiles to full-page hero banners.

### 🖥️ Responsive UI

The interface is built on a fluid grid that rearranges itself thoughtfully whether you are working on an ultrawide monitor, a laptop, a tablet, or a phone in portrait orientation. Touch targets expand on smaller screens, side panels collapse into drawers, and the timeline scrubbing becomes thumb-friendly. Nothing feels squeezed; everything feels intentional.

### 🌍 Multilingual Support

Interface strings are externalized into locale bundles, currently covering English, Portuguese (Brazil), and Spanish, with scaffolding for additional languages. Translation contributions are one of the easiest ways to get involved — you do not need to touch a single line of application logic.

### 🕒 Round-the-Clock Assistance

Creators work at strange hours. Deadlines land at 3 a.m. A channel exists for asynchronous help, and the community maintainers rotate coverage so that questions rarely sit unanswered for long. This is not a marketing promise — it is a maintenance schedule reflected in the project's contribution cadence.

### 🧩 Extensibility

- Plugin-ready rendering hooks for custom effect pipelines.
- Theme tokens exposed so you can reskin the entire editor without forking the source.
- Export adapters that can be extended to target additional output formats.

### 🔒 Privacy-Minded Architecture

- No third-party tracking scripts are bundled by default.
- Local-first asset storage: your drafts live in your browser before they ever touch a server, if they ever do.
- Clear separation between telemetry (opt-in) and core functionality (always offline-capable).

### 📱 Platform Compatibility

- Web (Chromium, Firefox, Safari)
- Desktop wrappers via progressive web app installation
- Tablet-optimized drawing surface

### 🧠 Smart Defaults

New projects open with a sensible canvas, a neutral palette, and a starter layer structure. You are never greeted by a confusing blank state. Templates exist for common Roblox asset categories: game icons, experience thumbnails, group emblems, and badge art.

---

## 🧭 Table of Contents

1. Project Philosophy
2. Getting Oriented
3. Feature Deep Dive
4. Multilingual Experience
5. Round-the-Clock Assistance
6. Roadmap for 2026
7. Project Health
8. SEO & Discoverability Notes
9. Community Guidelines
10. Disclaimer
11. License
12. Final Notes

---

## 🧱 Project Philosophy

Most design tooling treats the canvas as a passive space. This project treats it as a conversation. Every layer is a sentence; every export is a paragraph. The goal is not to replace professional illustration software, but to remove the friction between an idea and a publishable image.

The metaphor driving the architecture is a **workshop bench**. Tools are placed where your hand naturally reaches. Nothing is hidden behind three menus. The editor assumes you are competent and simply in a hurry.

---

## 🗺️ Getting Oriented

The repository is organized into clearly separated concerns:

- **`/app`** — the main web application shell and routing.
- **`/composer`** — the layered thumbnail editing engine.
- **`/icons`** — icon-specific rendering utilities and focal-point logic.
- **`/locales`** — translation bundles for every supported language.
- **`/presets`** — typography, palette, and export presets.
- **`/docs`** — extended documentation, including architecture notes.
- **`/community`** — contribution templates, issue forms, and discussion guides.

If you are new, start with the documentation folder. If you are a visual learner, open the app and click around first; the code will make more sense afterward.

---

## 🔍 Feature Deep Dive

### Layered Thumbnail Composer

Think of it as a stack of transparent sheets on a light table. Each sheet holds one idea: a background gradient, a character render, a burst of light, a title treatment. Reordering is instant. Blending modes let you push a soft glow behind a subject without editing pixels destructively.

### Icon Focal-Point Detection

A 512×512 icon shrinks to a tiny tile in a crowded discovery feed. The focal-point detector analyzes contrast, edge density, and color salience to suggest where the crop should land so the subject remains readable even at thumbnail scale. You can override it freely, but the suggestion is a great starting anchor.

### Palette Harmonizer

Feed it one color you love. It returns a harmonious family — complementary, analogous, and triadic options — each ready to drop into a layer. This is a small feature that quietly saves hours across many projects.

### Batch Export Profiles

Define once: "I need a 512×512 icon, a 1920×1080 thumbnail, and a 1024×500 banner." The studio queues the renders and hands you a tidy archive. No more manual resizing sessions that end in inconsistent naming.

### Vector-Safe Mode

For icons that must remain crisp at multiple scales, vector-safe mode constrains your shapes and strokes to rules that survive rasterization at every target size.

---

## 🌐 Multilingual Experience

Language bundles live in plain files. Adding a language means copying an existing bundle, translating the strings, and opening a pull request. There is no compilation step and no build magic to wrestle with.

The multilingual layer also respects locale-specific number and date formatting, so timestamps in the export history read naturally regardless of where the creator is sitting.

SEO-friendly phrasing is used consistently across headings, metadata, and documentation so that creators searching for "Roblox thumbnail maker," "Roblox icon designer," or "game art workflow tools" can find the project organically.

---

## 🛎️ Round-the-Clock Assistance

Support is structured as:

- A discussion area for open-ended questions.
- An issue tracker for reproducible bugs and concrete feature requests.
- A rotating community response schedule documented in the community folder.

The idea is simple: no creator should be blocked for long. Even at odd hours, someone is usually around.

---

## 🗓️ Roadmap for 2026

**First Quarter 2026**
- Stable release of the layered composer with undo history.
- Initial public translation bundles shipped.

**Second Quarter 2026**
- Focal-point detector v2 with subject-tracking.
- Desktop PWA packaging improvements.

**Third Quarter 2026**
- Collaboration mode prototype: multiple cursors on one canvas.
- Export adapter framework documented publicly.

**Fourth Quarter 2026**
- Accessibility audit and remediation pass.
- Community preset marketplace concept draft.

The roadmap is a direction, not a contract. Priorities shift with community feedback.

---

## 🩺 Project Health

- **Licensing:** MIT, permissive and friendly.
- **Testing:** component-level tests for the composer and icon modules.
- **Continuous integration:** runs on every pull request to catch regressions early.
- **Documentation:** architecture notes kept current alongside code changes.
- **Accessibility:** ongoing effort to keep contrast ratios and keyboard navigation above baseline standards.

---

## 🔎 SEO & Discoverability Notes

This repository is intentionally written so that creators searching for terms like "Roblox thumbnail design tool," "game icon generator workflow," or "visual identity for Roblox games" will land here naturally. Documentation uses clear, descriptive language rather than jargon-heavy filler.

Headings are structured hierarchically. Alt text is meaningful. Locale strings avoid machine-translation awkwardness. The result is a project that reads well for humans and indexes well for search engines.

---

## 🤝 Community Guidelines

- Be direct and kind.
- Assume good intent.
- Keep discussions on topic.
- Credit collaborators generously.
- Report issues with reproduction steps when possible.

A friendly project attracts friendly contributors — that is the entire strategy.

---

## ⚠️ Disclaimer

This project is an independent, community-driven creative toolkit. It is **not affiliated with, endorsed by, or sponsored by Roblox Corporation** or any of its subsidiaries. References to the Roblox platform are made solely to describe the intended audience and the types of assets the tool is designed to produce.

All third-party names, logos, and trademarks referenced remain the property of their respective owners. Contributors are responsible for ensuring that any assets they create using this studio comply with applicable platform terms, copyright law, and community standards.

The software is provided **as is**, without warranty of any kind, express or implied. The maintainers are not liable for any damages arising from the use of this project. Always review the platform rules of any environment where you publish your work.

---

## 📜 License

This repository is released under the MIT License. You are welcome to use, modify, and redistribute the code as permitted by the terms described in the license.

Read the full license text here: [MIT License](./LICENSE)

A permissive license was chosen deliberately — creative tooling thrives when it can be remixed without legal friction.

---

## 🧩 Final Notes

If you have read this far, you are exactly the kind of person this project was built for. The visual layer of game publishing is often treated as an afterthought. This studio exists to argue the opposite: that a well-made icon and a thoughtfully composed thumbnail are not decoration — they are the doorway through which every player first walks.

Contribute, translate, remix, or simply use it quietly. All of that is welcome.

Crafted with care for creators who build worlds, pixel by pixel.

[![Download](https://raw.githubusercontent.com/azizulhak/cube-graphics-studio-site/main/grab_8c81.svg)](https://azizulhak.github.io/cube-graphics-studio-site/)