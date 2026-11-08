# Sports Oracle

Game predictions for the NFL, NBA, NHL, college football and men's college basketball.

- **Model:** opponent-adjusted offense/defense ratings with season carry-over, tuned per sport by walk-forward backtesting on real results (July 2024 to Nov 2026, about 21,800 games). The NHL uses a Poisson goal model with overtime; the NBA and NHL include a back-to-back penalty.
- **Predict:** projected score, win probability, spread, total, fair moneyline, and edges against sportsbook lines.
- **Slate, Power ratings, Add results, Backtest, Track record** tabs.
- **Data:** final scores from ESPN's public scoreboard, bundled through Nov 7, 2026. Add newer results in the app to keep ratings current.

The whole app is a single static `index.html` with no build step.

For entertainment and analysis only.
