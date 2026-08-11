# Changelog

## Unreleased

- Perf: drag-select now toggles `.selected` classes on existing DOM nodes instead of
  re-rendering the whole plate grid on every hovered well.
- Add localStorage autosave (debounced) with a restore-last-session prompt on load.
- Add keyboard navigation: arrow keys move/extend selection, Enter opens the cell
  editor, Escape clears selection.
- Add touch support for drag-select and move-mode on plate/vial-holder grids, with
  double-tap to open a well's editor.
- Add collapsible sidebar.
- Add adjustable well zoom (60%-160%).
- Add a progress bar in the sidebar reflecting completed workflow steps.
