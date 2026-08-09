# 🌿 Yuvi's Boards

A personal, single-file **Trello / Monday-style board app** — no installs, no server, works fully offline. Just open `boards.html` in a browser.

Built by [Yuval Knobel](https://www.linkedin.com/in/yuval-knobel-248ba2174/).

## Features

- **Topics** in a sidebar — each is its own board (add, rename, reorder by drag, delete). Each topic has its own accent color.
- **Columns** — add, rename, delete, drag to reorder, and drag the right edge to resize (width is remembered).
- **Cards** — quick inline title editing, drag between/within columns, duplicate (⧉), and a full editor (✎) for:
  - **Labels** (color dots)
  - **Due dates** (with "today / soon / overdue" pills)
  - **Notes**
- **Done checkmark** with a 🎉 confetti burst, plus a per-board **"Hide done"** toggle.
- **Progress bar** per board (done / total).
- **Quick search** across every board.
- **Hebrew / RTL** support with an embedded, offline **Assistant** font.
- **Light / Dark / System** theme (⚙ Settings).
- **Backup / Restore** your boards to a JSON file.

## Data & privacy

Everything is stored **locally in your browser** (`localStorage`) — nothing is sent anywhere. Use **⬇ Backup** to save a JSON copy, and **⬆ Restore** to load it (backups from older versions are auto-migrated).

## Usage

Open `boards.html` in any modern browser (best on a recent Safari/Chrome — it uses CSS `color-mix`). On macOS:

```bash
open boards.html
```

## Tech

Plain HTML + CSS + vanilla JavaScript in a single self-contained file. No dependencies, no build step. The Assistant font (OFL) is embedded as base64 so it works offline.
