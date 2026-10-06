# Velvet Room Casino

A free-play casino web app built for iPhone: slots, blackjack, roulette, video poker, baccarat and crash, all with play-money chips.

- **No real money.** Chips can't be bought, cashed out or exchanged for prizes. You start with 1,000 and can top up for free whenever you run out.
- **One file.** Everything lives in `index.html`. There's no build step and no server code.
- **Saves on your phone.** Your chip count, bet sizes and recent results are kept in the browser's local storage.

## Games

| Game | Rules |
| --- | --- |
| Diamond Sevens (slots) | 3 reels, 1 payline. Three of a kind pays 5× to 150×; two cherries pays 2×. |
| Blackjack | 6-deck shoe, dealer stands on all 17s, blackjack pays 3 to 2, double down on your first two cards. |
| Roulette | Single-zero wheel. Straight-up numbers pay 35 to 1, columns and dozens 2 to 1, red/black, odd/even and high/low pay even money. |
| Jacks or Better (video poker) | Five-card draw from one deck. Hold, draw once. Pays 1× for jacks or better up to 250× for a royal flush. |
| Baccarat | Punto banco from an 8-deck shoe with standard third-card rules. Player pays 1 to 1, Banker 19 to 20, Tie 8 to 1 (Player/Banker bets push on a tie). |
| Crash | A multiplier climbs until a random crash point. Cash out before it crashes, or set an auto cash-out from 1.2× to 10×. |

## Put it on your iPhone

1. Host the folder anywhere that serves static files. With GitHub Pages: repo **Settings → Pages**, pick this branch and the root folder, then save.
2. Open the Pages URL in Safari on your iPhone.
3. Tap **Share → Add to Home Screen**. It opens full screen with its own icon, like an app.

To try it locally, open `index.html` in any browser.
