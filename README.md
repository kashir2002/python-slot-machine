# Python Terminal Slot Machine

A text-based slot machine game built entirely in Python. Deposit your virtual cash, choose your lines, place your bets, and spin the wheels to see if you win!

## Features
* **Dynamic Betting:** Choose how many lines to bet on (1-3) and how much to bet per line.
* **Wallet Tracking:** The game tracks your balance across multiple spins. You can't bet money you don't have!
* **Randomized Spins:** Uses Python's `random` module to generate a 3x3 grid based on weighted symbol probabilities.
* **Win Multipliers:** Different symbols have different values and rarities—hitting the rare symbols pays out more.

## How to Play

### Prerequisites
You just need Python installed on your computer. No external libraries or packages are required.

### Running the Game
1. Clone this repository to your local machine:
   `git clone https://github.com/YOUR-USERNAME/python-slot-machine.git`
2. Navigate into the project folder:
   `cd python-slot-machine`
3. Run the script:
   `python slottere_machine.py` 

## 📖 Game Rules
1. **Deposit:** Start by entering the amount of money you want to play with.
2. **Lines:** Choose to bet on 1, 2, or 3 lines. (Betting on 2 lines checks the top and middle rows; betting on 3 checks all rows).
3. **Bet Amount:** Enter how much you want to bet *per line*. Your total bet is `Lines × Bet Amount`.
4. **Winning:** If a line contains 3 matching symbols across the columns, you win! Your payout is determined by the value of the winning symbol multiplied by your base bet.

## 🛠️ Built With
* Python 3