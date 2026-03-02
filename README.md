# Kalshi v Polymarket: Deconstructing War-Time Bets

When I sat down to work on this project, every other minute I found myself glued to on screen or another, looking for updates on what's happening in the Middle East. So I decided to make a hard pivot, and cover how prediction markets had reacted to this war in 2025 and now. 

This data analysis compares prediction market activity on Kalshi and Polymarket during two Iran-related conflict periods: the June 2025 12-Day War and the February 2026 U.S. strikes.

TLDR: it's getting worse!

**[Read the story](https://areebafatimaa.github.io/kalshi-polymarket-iran/)**

## About

This project analyzes how bettors on two major prediction market platforms dealt with real-time geopolitical events, including trading volumes, market types, regulatory differences, and how betting patterns shifted between the two conflict periods.

Key findings:
- Polymarket generated $943 million in Iran-related trading volume during the 2026 strikes, 143x more than Kalshi's $6.6 million
- Betting volume increased 5.4x between the June 2025 war and the 2026 escalation
- The top 10 markets account for 82% of all trading volume

## Data

| File | Description |

| `polymarket_iran_markets.csv` | 33 Polymarket Iran-related markets with prices, volumes, and status |
| `kalshi_iran_markets.csv` | 11 Kalshi Iran markets with outcome probabilities and volumes |
| `polymarket_money_makers.csv` | Top 20 profit-makers across both conflict periods | Ended up not using it in the data viz

Polymarket data was collected via the [Gamma API](https://gamma-api.polymarket.com). Kalshi data was collected manually from [kalshi.com](https://kalshi.com/category/politics/iran). All data as of March 1, 2026.

## Analysis Notebooks

- `polymarket_analysis.ipynb` - Polymarket market analysis and visualizations
- `kalshi_analysis.ipynb` - Kalshi market analysis and top money-makers breakdown

## Built With

- [D3.js](https://d3js.org/) v7 for interactive charts
- [Scrollama](https://github.com/russellsamora/scrollama) for scroll-driven storytelling

## Author

[Areeba Fatima](https://areebafatimaa.github.io)

## Cover image

Designed on Canva (free)
