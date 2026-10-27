# Intrinsa – Support Site

This repository hosts the public support page and privacy policy for **Intrinsa**, an iPhone app that estimates a listed company's intrinsic value using several independent valuation methods.

- **Support:** https://YOURUSERNAME.github.io/intrinsa/
- **Privacy Policy:** https://YOURUSERNAME.github.io/intrinsa/privacy.html

## About Intrinsa

Type a company name or ticker and Intrinsa returns a structured valuation report:

- **Blended fair value**, combining methods weighted by how well they suit the company
- **Valuation by method:** discounted cash flow (DCF), peer comparables (P/E, EV/EBITDA, EV/Revenue, P/B), net asset value, residual income and the dividend discount model
- **Monte Carlo range:** 1,000 simulated DCF outcomes (P10, median, P90)
- **Analyst context:** mean target, target range and consensus, shown for reference
- **Next-day forecast:** an LSTM-based price prediction, reported with its validation error
- **Charts:** price against valuation, and a football-field chart of valuation ranges
- **Watchlists and saved reports:** value several tickers in one run and reopen past results

Intrinsa connects to a valuation server, using a server address and API key entered in the app's Settings.

## Repository contents

| File | Purpose |
|------|---------|
| `index.html` | Support page: features, getting started, methods, FAQ, troubleshooting and contact |
| `privacy.html` | Privacy policy |

Both pages are self-contained HTML. Styles and the app icon are embedded, so no build step or extra files are needed.

## Getting help

For questions, bug reports or feature requests, email **support@example.com**. Please include your device model, iOS version, app version and the ticker you were valuing.

## Disclaimer

Intrinsa provides model estimates for information and education only. They are not investment advice, a recommendation to buy or sell any security, or a guarantee of future performance. Always do your own research and consult a qualified financial adviser before investing.

---

© 2026 Intrinsa. All rights reserved.
