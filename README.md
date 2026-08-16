# 3BR Layout

A to-scale, single-file floor plan tool for thinking through furniture layouts.

**Live:** https://killiancoyote.github.io/apartment-layout/

- Plan drawn to scale in inches, with walls, columns, doors, windows and fixtures
- Tap a piece from the catalog to drop it in; drag to move, `R` to rotate 90°
- Live clearance dimensions to the walls, flagging tight walkways under 30"
- Collision detection against furniture, closets, counters and structural columns
- Pull-out zones for pieces that extend (sofa beds, trundles)
- Custom pieces saved to their own reusable tab
- Named plans: save, reopen, rename, duplicate, delete

No dependencies, no build step. Everything lives in `index.html` and persists to
`localStorage`.

## Keyboard

| Key | Action |
| --- | --- |
| `R` | Rotate 90° |
| Arrows | Nudge 1" (`Shift` for 1') |
| `Delete` | Remove selected |
| `Cmd/Ctrl+Z` | Undo |
| `Esc` | Deselect |
