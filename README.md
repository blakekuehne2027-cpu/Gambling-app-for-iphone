# Velvet Room Casino

A free-play casino web app built for iPhone: 21 games in a lobby, from mines and plinko to blackjack and craps, all with play-money chips.

- **No real money.** Chips can't be bought, cashed out or exchanged for prizes. You start with 1,000 and can top up for free whenever you run out.
- **One file.** Everything lives in `index.html`. There's no build step and no server code.
- **Saves on your phone.** Your chip count, bet sizes and recent results are kept in the browser's local storage.

## Games

All 21 games share one chip balance. Open any of them from the lobby.

| Group | Game | Rules |
| --- | --- | --- |
| Originals | Mines | 5×5 grid with 1–24 hidden mines. Each gem raises the multiplier; cash out any time. |
| Originals | Plinko | 12 rows of pegs, 13 slots. Low, medium and high risk payout tables. |
| Originals | Crash | A multiplier climbs until a random crash point. Cash out by hand or set an auto cash-out. |
| Originals | Limbo | Pick a target from 1.1× to 100×; win if the result reaches it. |
| Originals | Dice | Roll 0–99.99 under or over a target you set with a slider. |
| Originals | Tower | Climb 8 floors with one trap per floor. Easy, medium or hard. |
| Originals | Keno | Pick up to 10 of 40 numbers; 10 are drawn. |
| Originals | Coin Flip | 1.96× per win, then collect or flip again for double or nothing. |
| Originals | Lucky Scratch | Scratch the foil with your finger; three matching prizes win. |
| Cards | Blackjack | 6 decks, dealer stands on 17, blackjack pays 3 to 2, double down. |
| Cards | Jacks or Better | Video poker: hold and draw once. Up to 250× for a royal flush. |
| Cards | Baccarat | Punto banco with standard third-card rules and a bead road. |
| Cards | Hi-Lo | Call higher or lower on the next card to grow a multiplier. |
| Cards | Red Dog | Bet the third card falls between the first two. Narrow spreads pay up to 5 to 1. |
| Cards | Casino War | High card wins. On a tie, go to war or surrender half. |
| Slots & wheels | Diamond Sevens | 3-reel, 1-payline slot. |
| Slots & wheels | Roulette | Single-zero European wheel with inside and outside bets. |
| Slots & wheels | Money Wheel | The Big Six wheel: 1, 2, 5, 10, 20 and two 40-to-1 spots. |
| Dice & racing | Craps | Pass line and don't pass, with the point puck. |
| Dice & racing | Sic Bo | Three dice: big/small, odd/even, totals, singles and any triple. |
| Dice & racing | Velvet Derby | Six horses with fixed odds; back one and watch the race. |

## Put it on your iPhone

1. Host the folder anywhere that serves static files. With GitHub Pages: repo **Settings → Pages**, pick this branch and the root folder, then save.
2. Open the Pages URL in Safari on your iPhone.
3. Tap **Share → Add to Home Screen**. It opens full screen with its own icon, like an app.

To try it locally, open `index.html` in any browser.
