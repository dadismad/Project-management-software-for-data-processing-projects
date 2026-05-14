# 間 · Interval Tracker

> *meaningful intervals · 意味のある間*

A single-file project tracker styled in the Japanese ink (irezumi) tradition. Bold kumo cloud SVGs frame an open, frameless layout rendered in cerulean blue and muted gold. All data persists in the browser via `localStorage` — no backend required.

**Live:** [https://dadismad.github.io/Project-management-software-for-data-processing-projects/](https://dadismad.github.io/Project-management-software-for-data-processing-projects/)

---

## Projects

### 知 · Geopolitical Lens
Captures a friend's interpretations of geopolitical and economic events — tasks, milestones, and reflective notes on how the world is being read.

### 語 · Narrative Interpreter
Long-term personal narrative tracking — recording the arcs, themes, and insights that emerge over time.

---

## How to use

1. **Open** `index.html` locally in any modern browser, or visit the live GitHub Pages link above.
2. **Select a project card** (知 or 語) to open its workspace panel below.
3. **Plan tab** — type a task or milestone and press **Add** (or Enter). Click the gold checkbox to mark it done; click ✕ to delete it.
4. **Reflect tab** — write a freeform insight and click **Save insight**. Entries are stored with today's date.
5. The **progress bar** and stats (planned / done / insights) update automatically.
6. Everything is saved in `localStorage` in your browser — no account or server needed.

---

## Stack

- Single `index.html` — HTML, CSS, and vanilla JS, no build step
- Google Fonts: Cormorant Garamond + Noto Serif JP
- GitHub Pages for hosting (auto-deployed via `.github/workflows/pages.yml`)
