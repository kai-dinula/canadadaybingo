# 🍁 Canada Day Human Bingo

A mobile-friendly 4×4 human bingo game for a Canada Day party. Players find people
at the party who match each square, tap the square, and type that person's name.
Progress is saved in the browser's localStorage, so reloading the page keeps the card.
First two players to fill all 16 squares present their card to the judges and win a
Blue Jays / Raptors hat.

## Hosting on GitHub Pages

1. Push this repo to GitHub.
2. On GitHub: **Settings → Pages → Source: Deploy from a branch**, pick `main` and `/ (root)`, save.
3. The game will be live at `https://<your-username>.github.io/canadadaybingo/` within a minute or two.
4. Share the link (or a QR code pointing at it) with party guests.

Everything is in a single `index.html` — no build step, no dependencies.

## Notes

- Game state is saved per-device under the localStorage key `canadaDayBingo.v1`.
- "Start over" clears the card but keeps the player's name.
- To change the questions, edit the `QUESTIONS` array at the top of the `<script>` in `index.html`.
