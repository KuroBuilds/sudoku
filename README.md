# Kid Sudoku 🧩

A friendly Sudoku game for kids. Runs in any browser, installs to a phone's
home screen like an app, and works **offline** after the first visit.

**Play:** https://kurobuilds.github.io/sudoku/

- Grid sizes: 4×4 Mini, 6×6 Junior, 9×9 Classic
- Levels: Easy, Medium, Hard. A new puzzle is generated every time, always with exactly one answer
- Helpers: highlighting, red for mistakes, "numbers left" counter, 3 hints, notes, undo
- 3 hearts per puzzle, stars and confetti when solved
- Progress saves automatically on the device. No accounts, no ads, no tracking

How to install and play: see [MANUAL.md](MANUAL.md).

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole game (HTML + CSS + JavaScript, no libraries) |
| `manifest.json` | App name, icon and colours for "Add to Home Screen" |
| `sw.js` | Service worker: stores the game on the device so it runs offline |
| `icon-*.png` | Home-screen and browser icons |
