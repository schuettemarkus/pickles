# Pickles

A pickleball scorekeeper and team generator for an 8-player guys weekend. It's one self-contained `index.html` with no build step and no dependencies.

**Run it:** open `index.html` in a browser, or turn on GitHub Pages for this repo and open it on your phone. Saved locally, data stays on that device. When it's hosted as a shared Claude artifact, scores sync live to every phone.

## Features
- **Sessions**: Friday night, Saturday morning, and so on. Each has its own courts (1 or 2), target score (11/15/21), scoring style and who's playing.
- **Team generator**: *Mixer* rotates partners and opponents across the whole weekend, *Balanced* evens out teams by rating, and *Random* has no memory. Sit-outs rotate fairly.
- **Live scoring**: tap the team that won the rally. Side-out mode keeps the `4–2–1` call and server number for you. Includes undo, first-serve switching, win-by-2 detection and manual score entry.
- **Standings**: W–L, point differential, last-5 form, hot streaks and an Elo-style rating. Filter by weekend or by session.
- **Trophies & partner chemistry**: best duo, biggest blowout, nail-biter, point hog, cold streak, and every pair's record.
- **Crude mode**: one toggle swaps real names for nicknames that can be edited or rerolled, and turns on trash-talk toasts.
- **Copy for group chat**: copies a text version of the standings.
