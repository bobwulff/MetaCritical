# Meta Critical (beta)

Guess the game from three critic reviews: its lowest-scored review, its highest, then IGN's (or a random outlet).

- Reviews: [OpenCritic](https://opencritic.com) API, top 500 games
- Older games' platforms: [RAWG](https://rawg.io)
- Designed by Bob Wulff, coded by Claude

## Files

- `index.html` — the whole game (data included)
- `art/` (optional) — box art named `<OpenCritic ID>.jpg`, shown when you win. If this folder is
  missing, the game tries OpenCritic's own image link instead.

Reports from the in-game report button go to a Google Form and land in its linked Google Sheet.
