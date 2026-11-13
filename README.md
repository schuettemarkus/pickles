# Pickles

An editable King's Court points leaderboard for an 8-player pickleball weekend. It's one self-contained `index.html`.

**Live site:** https://schuettemarkus.github.io/pickles/ (once GitHub Pages is turned on; see below)

## Sharing scores across phones
1. Open the site and tap **Create shared scoreboard**. The address changes to `…/pickles/#<board-id>`.
2. Tap **Copy link for the group** and send that link to everyone.
3. Everyone who opens the link sees and edits the same points. Other phones refresh every few seconds, and each phone remembers the board after that.

Scores are stored free on [JSONBlob](https://jsonblob.com), with no account. Anyone with the link can change points.

If the create button fails, go to jsonblob.com, tap **Save**, copy the ID from the address bar, and paste it into the **Board ID** box.

**Never loses a tap:** each phone stores its own tally in the board, and the total is the sum of all of them. If two phones save at the same moment and one overwrites the other, the overwritten phone puts its tally back within a few seconds.

## Turn on GitHub Pages (one time)
Repo **Settings → Pages → Build and deployment**: set Source to **Deploy from a branch**, pick branch `claude/admiring-turing-u2a2yu` and folder `/ (root)`, then **Save**. The site goes live at the URL above within a minute or two.
