# Kotel Fighter 90 — Family Fight Game

A retro, 90s-DOS-style pixel fighting game starring the family. Pick your fighter, the CPU picks its own, and you battle it out in front of the Kotel.

## Play

Just open `index.html` in a browser — it's a single self-contained file, no build step or server needed. (Or enable GitHub Pages for this repo and share the link.)

## Controls

**Keyboard**
- Arrow keys: move / jump / block (hold ↓)
- `J`: punch · `K`: kick · `L`: special move

**Mobile**
- Rotate to landscape when prompted
- Left side: "+"-shaped D-pad for movement
- Right side: punch / kick / special buttons

## Customizing the roster

Edit the `ROSTER` array near the top of the `<script>` in `index.html` — each entry controls a fighter's name, nickname, colors, stats, and special-move name. Everything is drawn procedurally on canvas (no image assets), so recoloring or restyling a fighter is just editing hex values.
