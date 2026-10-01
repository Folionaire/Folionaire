# Folionaire - Live Demo

A complete portfolio tracker in a single HTML file. ASX, US stocks and crypto. No account. No subscription. No cloud. Your data never leaves your device.

▶ [Try the live demo](https://folionaire.github.io/Folionaire/) &nbsp;|&nbsp; 💰 [Get the full version, A$49 once](https://folionaire.gumroad.com/l/folionaire)

## Why it exists

I was tracking ASX shares, US shares and crypto across a spreadsheet and three separate apps. The alternatives each had a catch: free tiers that cap out, subscriptions that keep rising, or tools that wanted read access to my brokerage. So I built the thing I wanted, then polished it enough to sell.

The whole app is one HTML file. Open it in any browser on any device, no install and no login. Your holdings live in your browser's local storage and in JSON files you save yourself. The only network requests are fetching prices and optional news.

## What's in the full version

**Dashboard**
- Live market tape across the top: ten markets of your choosing, or add any Yahoo symbol or CoinGecko id
- Needs Attention gathers targets reached, parcels nearing twelve months, dividends due and thesis triggers into one panel
- Risk Flags warn when a position grows past your size limit or falls past your drawdown limit
- Allocation donut beside the value chart, portfolio and crypto movers, GICS sector performance, headlines with sentiment
- Optional TradingView charting with every holding as a one-tap shortcut

**Portfolio**
- Unlimited holdings, transactions and portfolios (partner, kids, super as separate tabs with a combined view)
- Portfolio value chart with 1D through ALL ranges, in AUD, USD or combined
- Sortable holdings table with a weight column, totals row, allocation and sector breakdowns
- Transaction history that totals buys, sells, realised P&L and net cash for whatever filter you set

**Australian tax**
- CGT with FIFO parcel matching and the 12-month discount test
- Brokerage included in the cost base
- Capital losses offset against gains before the 50% discount, which is the ATO order
- Prior-year capital losses
- AMIT cost base adjustments from your annual AMMA statements
- Returns of capital, and share splits and consolidations
- Dividend and franking credit tracking, with DRP parcels and foreign withholding tax

**Planning and analysis**
- War Room: set a size cap, buy-in levels, a buy floor, an alarm and an exit for each holding before you need them, write your thesis as numbers that could prove you wrong, and check the 52-week range and seven business fundamentals
- Exit Strategy: what to sell at 2x, 3x or any multiple to recover your original money and hold the rest for free, plus the Folionaire Ladder (take double off the table, then step down through widening stops), laddered exits and trimming to a target allocation
- Wealth Plan: your FI number, the year you reach it, and whether your outside-super pot bridges the gap to preservation age
- Budget: income vs expenses vs invested, weekly through yearly, with spending by category and insights that read your entries
- Portfolio Risk Scan scoring concentration, diversification, asset mix, crypto risk, loss control, income and currency exposure
- Trading Insights: win rate, expectancy, streaks and pattern analysis by reason and emotion

**Data and tools**
- JSON backup that restores everything, CSV export, and Plain Text Accounting ledger export for hledger and beancount
- CSV import with column auto-detection for Sharesight, Navexa, Binance, Coinbase, CoinGecko, CoinMarketCap, Crypto.com and generic broker exports
- Watchlists with price alerts and reminders
- News and sentiment terminal, free out of the box via Google News, Yahoo Finance and Motley Fool AU, optional free API keys for more
- Crypto wallet scanner from a public address (BTC, ETH, SOL, BNB, POL)
- Four themes including Terminal, light and dark
- Privacy mode that hides every figure and blurs charts
- Five CGT parcel methods, a one-page tax report and debt recycling tracking
- Folder Sync: write straight to a file in your own Dropbox or OneDrive folder, no account or server
- Optional TradingView market widgets, off by default and never fed your holdings
- Optional Solana RPC so wallet scans are not throttled by public endpoints
- Solana scans cover both SPL Token and Token-2022 holdings
- Free updates for the life of v1. v2 onwards is a A$10 upgrade for existing owners
- Full source code in the file. Works offline

## What it does not do

Being straight about the gaps so nobody finds out the hard way:

- No broker sync. Entry is manual or CSV import
- Display currencies are AUD and USD
- Managed funds only work where Yahoo Finance lists a ticker
- Tax figures are estimates. Have a registered tax agent review a full financial year of output before you rely on them

## Latest release

**v1.2** added the War Room, the Folionaire Ladder and budget insights, and rebuilt the dashboard around one question: open the app and know what you own, what moved, and what needs a decision. Market tape, Needs Attention, Risk Flags, allocation donut, crypto movers, sector heatmap, headlines and optional charting. Portfolio and transaction history finally total. Full changelog ships with the download.

## Demo limits

The demo runs on sample data and resets when you refresh. Saving, exporting and importing are disabled, and creation is capped (15 transactions, 5 watchlist entries, 5 calendar events, 10 terminal scans a day). Everything else is the real app.

---

This repo hosts the evaluation demo only. See LICENSE.
