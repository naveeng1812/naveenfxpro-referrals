# NaveenFXpro — Referral Links

The personal referral hub for [NaveenFXpro](https://www.youtube.com/@NaveenFXpro):
the trading platforms I actually use, with my referral codes, plus my YouTube channel.

Live: https://naveeng1812.github.io/naveenfxpro-referrals/

## What it is

A single self-contained `index.html` — no build step, no dependencies, no tracker.
The photo and all four brand logos are embedded as data URIs, so the page works
offline and can be hosted anywhere (GitHub Pages, Netlify, Cloudflare Pages).

## Editing

Everything is plain HTML inside `index.html`:

- **A card** — copy one `<article class="card">` block and change the brand,
  category, description, then update BOTH URLs: the `href` on the link and the
  `data-copy` attribute on the Copy button.
- **Photo** — replace the base64 string in the `<img>` inside `.portrait__frame`.
- **Logos** — each is a 96x96 data URI in the `.card__logo img`.
- **Colours** — CSS custom properties in `:root` and the dark-mode block.

## Referral links

| Brand | Link |
| --- | --- |
| Earn2Trade | https://www.earn2trade.com/?a_pid=NAVEENFX |
| FundedNext | https://fundednext.com/?fpr=NAVEEN |
| Zuperior | https://dashboard.zuperior.com/login?referralCode=NAVEENFX |
| TradingView | https://in.tradingview.com/pricing/?share_your_love=naveeng1812 |
| YouTube | https://www.youtube.com/@NaveenFXpro |

Referral disclosure and a trading-risk note are in the page footer.

## Deploy

Served by GitHub Pages from the `main` branch, root folder.
