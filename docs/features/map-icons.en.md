# Reimagined mining Minesweeper

I've reworked the mining **Minesweeper** tool around how I believe it should work: a practical way to mark cave tiles and interpret dust warnings, rather than a system that pretends to know which tiles are safe.

- **Mark tiles yourself:** Cycle through a red cross, green check, purple question mark, or no mark.
- **Record dust clues automatically:** When the game reports a cave dust warning, the client displays a numbered clue from 1 to 8. Temporary clues expire after 30 minutes; you can pin them to keep them.
- **Inspect nearby tiles:** Hover over a clue to highlight its eight neighboring tiles and review the conditions recorded when the dust appeared.
- **Keep your notes:** Manual marks and pinned clues are saved with the map, while temporary observations disappear when you exit the client.

The Minesweeper annotation cursor keeps marking clicks separate from mining actions. Automatic mining-stop protections remain an independent setting. **Clues help you plan, but they never guarantee that mining is safe.**

[Mining safety and annotations](mining-safety.en.md)

[Back to features](../../README.md#features)
