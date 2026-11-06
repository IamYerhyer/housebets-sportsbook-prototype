# Housebets Sportsbook — Design Prototype

A clickable, front-end-only sportsbook prototype built for the Housebets "Sportsbook is coming" design contest ($15,000).

**Live demo:** https://iamyerhyer.github.io/housebets-sportsbook-prototype/

## Pages
1. **Sports home** — live now, starting soon, top competitions, sports nav, working search (teams, sample players, competitions, markets)
2. **Live** — every match in play, filters by sport and competition, live scores and ticking clocks, empty state shows Starting soon
3. **Football** — Premier League, Champions League, LaLiga, Serie A, Bundesliga; match-result odds on every row; follow a team or competition
4. **Match page** — Arsenal v Brighton (live): scoreboard, market groups (Popular, Goals, Halves, Handicaps, Goalscorers, Corners & Cards), odds move, markets suspend
5. **Bet slip + My bets** — singles only, decimal odds, stakes in USDT, odds-changed (must accept), suspended, placed and failed states; My bets with open / settled / cash out

Works at 390px (bet slip becomes a bottom bar) and 1440px (Housebets shell: top bar, left nav, side panel). Sample data only — no real players, no real money.

## V2 — Polymarket-grade pass
- **Light / dark mode toggle** in the top bar (choice is remembered)
- Match page: live **win-probability bar** implied from the odds, an **odds-movement chart** with the 23' goal marked, and traded-volume on every market
- Bet slip: **quick-stake chips** (10 / 25 / 50 / 100 / Max) and implied win chance per single
- Football: day filters (Live only / Today / Tomorrow / Weekend); featured matches carry volume + sparkline trends

Built by hand in HTML/CSS/JavaScript with Muse (Lyght). No templates or UI kits.
18+ · Gamble responsibly.
