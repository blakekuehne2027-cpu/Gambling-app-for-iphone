# Velvet Room Casino

A free-play casino web app built for iPhone: slots, blackjack and European roulette, all with play-money chips.

- **No real money.** Chips can't be bought, cashed out or exchanged for prizes. You start with 1,000 and can top up for free whenever you run out.
- **One file.** Everything lives in `index.html`. There's no build step and no server code.
- **Saves on your phone.** Your chip count, bet sizes and recent roulette spins are kept in the browser's local storage.

## Games

| Game | Rules |
| --- | --- |
| Diamond Sevens (slots) | 3 reels, 1 payline. Three of a kind pays 5× to 150×; two cherries pays 2×. |
| Blackjack | 6-deck shoe, dealer stands on all 17s, blackjack pays 3 to 2, double down on your first two cards. |
| Roulette | Single-zero wheel. Straight-up numbers pay 35 to 1, columns and dozens 2 to 1, red/black, odd/even and high/low pay even money. |

## Put it on your iPhone

1. Host the folder anywhere that serves static files. With GitHub Pages: repo **Settings → Pages**, pick this branch and the root folder, then save.
2. Open the Pages URL in Safari on your iPhone.
3. Tap **Share → Add to Home Screen**. It opens full screen with its own icon, like an app.

To try it locally, open `index.html` in any browser.
