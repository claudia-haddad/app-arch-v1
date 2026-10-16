# App architecture v1

A clickable Kalshi mobile navigation prototype.

- **Trade:** Trade and Talk views, with Live inside Trade.
- **Inbox:** Chats, notifications, combined unread count, and a Start a chat prompt.
- **Portfolio:** Compact balance and chart, positions, and Profile. The navigation label shows $4.2K.
- **Invest:** Theme-based market discovery.
- **Search:** Sample AI search and a leaderboard.

Every main tab includes an avatar shortcut to the social profile in the upper-right corner. The home header also includes an Earn $25 referral preview.

## Run locally

Open `index.html` in a browser, or serve this directory:

```sh
python3 -m http.server 8765
```

Then open http://localhost:8765.

## Demo data

All markets, odds, balances, activity, rankings, AI responses, and referral offers are illustrative. Trades and messages are simulated. No accounts, real-money transactions, or live AI services are connected. State resets when the page reloads.

This is a standalone concept prototype, not an official production Kalshi app.
