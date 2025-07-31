# ♠️ Blackjack Strategy Simulator

Simulates simplified blackjack between one player and a dealer.

## Features

- Classic strategy: Stand on 17 or higher, hit below.
- Card counting variant: If Hi-Lo count ≥ 2, stand on 15 or higher (simulate deck is “hot”).
- Tracks win rates for both strategies.

## How It Works

- One deck per game, shuffled fresh each round.
- Handles aces as 11 (or 1 if needed to avoid bust).
- Dealer always stands at 17+.

## Usage

Run the Python script or notebook to simulate 10,000+ games and compare win rates.

## Example Output

Classic strategy win rate: 0.4132
Card counting strategy win rate: 0.4170



