# LCMS Plate Layout Planner

A single-file, offline-first web app for planning fermentation -> LCMS sample-prep runs:
deepwell plates -> collect plates -> LCMS plate layout -> Xcalibur submission file.

Open `index.html` directly in a browser -- no build step, no server required.

## Features

- Editable 96-well (deepwell/collect/LCMS) and vial-holder grids with drag-select, a
  palette to batch-apply donor/compound/timepoint, and a per-well edit popover.
- Move mode (drag a well's contents elsewhere), copy/paste, undo/redo.
- Live-derived submission file (editable rows, duplicate-filename detection, CSV/TSV export).
- Built-in calculators: deepwell reagents, exposure mix (DMSO/PBS/drug), methanol + internal
  standard, calibration-line serial dilution.
- Printable experiment record export.
- Keyboard navigation (arrow keys, Enter to edit, Esc to clear selection).
- Touch/tablet support for drag-select (with double-tap to edit a well).
- Autosaves to `localStorage` and offers to restore your last session on reload.
- Collapsible sidebar and adjustable well zoom.

## Development

This is intentionally a single static HTML file (`index.html`) with inline CSS/JS --
no dependencies, no build. Edit it directly and refresh the browser to see changes.

## Changelog

See [CHANGELOG.md](CHANGELOG.md).
