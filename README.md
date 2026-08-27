# 🧵 Filament Shelf Builder

A single-file, no-install web app for laying out and printing a **3D-printer filament shelf map**. Built around the Jaycar / SUNLU filament range (catalogue codes like `TL6039`), but it works with any filament you add.

Type a catalogue code into a slot and it auto-fills the colour, filament type and colour name. Drag spools between slots to rearrange, then print a clean **A4 sheet** to stick on your shelf.

**▶ Live app: https://richdavies2005.github.io/filament-shelf-builder/**

## Why

Filament ranges change constantly — new colours get added, spools get moved around. This lets you re-map your shelf in seconds and reprint the label, instead of hand-editing a document every time.

## Features

- **Type a code → auto-fill.** Enter a `TLxxxx` code (or search by colour name) and the slot fills in the colour, type tag and name automatically.
- **Drag to rearrange.** Drag any filament onto another slot to swap their positions.
- **Auto-organise.** One click groups filaments by type (PLA, PLA+, PLA Silk…) and sorts each group in ascending CAT-number order — either laid out one type per row, or reflowed into your existing rows.
- **Flexible grid.** Add/remove rows, reorder rows, and set how many slots each row has.
- **Growing catalogue.** ~79 SUNLU filaments included out of the box. Add, edit or delete filaments as the range changes — light/dark text is auto-chosen from the colour's brightness (with a manual override).
- **Auto-save + backup.** Your layout and catalogue are saved in the browser automatically. Export/Import a JSON backup to keep it safe or move it to another computer.
- **Print / Save as PDF.** One click produces an A4 portrait sheet ready to print.

## Usage

No build step, no dependencies. Just:

1. Download `filament-shelf-builder.html`.
2. Double-click to open it in any modern browser.
3. Build your shelf, then **Print / Save as PDF (A4)**.

That's it — it runs entirely offline in a single file.

## Data & privacy

Everything lives in your browser's local storage on your own machine. Nothing is uploaded anywhere. The **Export backup** button writes a JSON file you fully control.

> Tip: local storage is per-origin, so a layout you build by opening the file directly (`file://`) is stored separately from one served over `http://`. Use Export/Import to move a layout between them.

## Licence

MIT — see [LICENSE](LICENSE).
