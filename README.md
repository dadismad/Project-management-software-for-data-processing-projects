# 間 · Interval Data Project Guide

> *meaningful intervals · 意味のある間*

A single-file static web app for non-technical project tracking, especially for projects built around data aggregation, processing, and interpretation. The interface uses a brighter sky-and-gold palette with irezumi-inspired kumo clouds and keeps everything in the browser via `localStorage` — no backend required.

**Live:** [https://dadismad.github.io/Project-management-software-for-data-processing-projects/](https://dadismad.github.io/Project-management-software-for-data-processing-projects/)

---

## Projects

### 知 · Geopolitical Lens
Collect signals, process notes, and record what the data suggests about geopolitical and economic events.

### 語 · Narrative Interpreter
Gather narrative material, process recurring patterns, and keep a clear interpretation trail over time.

---

## Guided workflow

Each project follows the same simple path:

1. **Gather data** — collect articles, files, notes, observations, or source material
2. **Process it** — sort, compare, clean, or group what you gathered
3. **Interpret it** — record what the pattern means or what action it suggests

The app recommends the next step automatically and includes a **ready-made workflow** button so a new project can start with sensible default tasks immediately.

---

## How to use

1. **Open** `index.html` locally in any modern browser, or visit the live GitHub Pages link above.
2. **Select a project card** (知 or 語) to open its workspace panel below.
3. In **Guided steps**, follow the suggested next step or click **Use ready-made workflow** to populate the project with starter tasks.
4. Add a task under **Gather data**, **Process it**, or **Interpret it**. Click the gold checkbox to mark it done; click ✕ to delete it.
5. In **Review**, write a short note about what the data showed and what should happen next.
6. The **progress bar** and stats (planned / done / insights) update automatically.
7. Everything is saved in `localStorage` in your browser — no account or server needed.

---

## Stack

- Single `index.html` — HTML, CSS, and vanilla JS, no build step
- Google Fonts: Cormorant Garamond + Noto Serif JP
- GitHub Pages for hosting (auto-deployed via `.github/workflows/pages.yml`)
