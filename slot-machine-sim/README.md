# 🎰 Slot Machine Monte Carlo Simulator

This project uses Python to estimate the average payout per spin from a simulated slot machine, using the Monte Carlo method.

## How It Works

- Runs the `play_slot_machine()` function many times (each spin costs $1).
- Tracks the payout for each spin (usually zero, occasionally a small or large win).
- Calculates your **average net profit (or loss) per play**.
- Demonstrates why most slot machines are negative expectation games!

## Usage

1. Open the notebook or script in this folder.
2. Run:

   ```python
   estimate_average_slot_payout(10000)

