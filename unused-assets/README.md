# Unused assets

Kept for reference; nothing here is loaded or built into the mod. Paths mirror
`src/main/resources/assets/electricadvantage/`.

- `textures/gui/container/` - vanilla-style GUIs made for the 1.10.2 mod
  (512x512, 2x scale). The 1.21.1 mod has no GUI textures, so these don't fit as-is.
- `textures/block/electric_pcb_printer_*.png` - the PCB printer, which isn't a block in 1.21.1.
- `textures/block/electric_drill_powered.png` - powered state; the 1.21.1 drill has none.
- Drill fix: `models/block/electric_drill_base.json`, `blockstates/electric_drill.json` and
  `textures/block/electric_drill_side.png` make the drill model point its legs and optic
  down by default (so the item shows them down) with a rotation-proof side texture. Placed
  drills look the same in every facing.
- Solar panel fix: `models/block/photovoltaic_generator.json` with
  `textures/block/photovoltaic_side.png` and `photovoltaic_front.png` puts the panel on top
  only, casing on the sides and a power-supply vent on the front.

To use a fix, copy its files over the matching ones in `src/main/resources`.
