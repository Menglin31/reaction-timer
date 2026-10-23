# reaction-timer

A direction arrow timer for reaction drills: shows arrows in 4 or 8 directions full-screen in fixed or random order, for directional reaction exercises such as the star excursion.

## Usage

Open https://menglin31.github.io/reaction-timer/ , adjust the settings, and tap "Start".

| Setting | Description |
|---|---|
| Order | Fixed (↑ → ↓ ← repeating) or Random |
| Directions | 4 (↑ → ↓ ←) or 8 (adds diagonals; fixed order goes clockwise ↑ ↗ → ↘ ↓ ↙ ← ↖) |
| Interval (sec) | Time between arrows, minimum 1 second |
| Set duration (sec) | 0 = no limit |
| Countdown before start (sec) | Time to get into position |

Tap the screen to stop while running. The screen stays awake during a set (requires browser support for the Wake Lock API).

## Files

| File | Description |
|---|---|
| `index.html` | The entire page (HTML + JavaScript), no dependencies |

## Deployment

GitHub Pages: Settings → Pages → Source: `Deploy from a branch`, Branch: `main`, `/ (root)`.
