# Pickles

A King of the Court tracker for an 8-player pickleball weekend. It's one self-contained `index.html` with no build step and no dependencies.

**Run it:** open `index.html` in a browser, or turn on GitHub Pages and open it on your phone. Saved locally, data stays on that device. As a shared Claude artifact, results sync live to every phone.

## How it works
- **Two courts: King's Court and Court 2.** Each round, tap the winning team on each court, then tap **Lock it in & rotate**.
- **Points:** each player on the winning King's Court team gets 1 point. Most points at the end of the weekend takes the pot.
- **Rotation:** King's Court winners stay, Court 2 winners move up, and King's Court losers move down. By default the winners split up and each takes a new partner, which suits individual points; a session setting keeps winning pairs together instead. With fewer than 8 players there's one court and a line of players waiting to get on.
- **Pot:** set the buy-in per person to see the pot total, the leader and a ranked list. Trophies cover longest reign, best King's Court pair, most promotions and the Court 2 regular. A button copies the standings for the group chat.
- **History:** every round is listed, and **Flip** fixes a King's Court winner that was tapped wrong. **Undo last round** reopens the round in progress.
- **Crude mode:** swaps in fixed nicknames.
