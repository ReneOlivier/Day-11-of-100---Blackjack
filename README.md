# Day-11-of-100---Blackjack
Day 11 of 100 days of code Python challenge by Angela Yu, Udemy Course

🃏 Blackjack Game (Day 11 of 100)

A simple command-line Blackjack game built in Python as part of my 100 Days of Code challenge.
This project simulates a classic Blackjack (21) game where the user plays against the computer (dealer). 
The game follows standard Blackjack rules including card dealing, score calculation, and win/lose conditions.

📌 Features
Random card dealing
Automatic dealer logic
Score calculation with Ace handling (11 or 1)
Win / Lose / Draw detection
Clean command-line interface
Replay option after each game

🛠 Tech Stack
Python 3
Jupyter Notebook

🚀 How to Run
Option 1: Run via Jupyter Notebook

Clone the repository:
git clone https://github.com/your-username/your-repo-name.git
Open the project folder.
Launch Jupyter Notebook:
jupyter notebook

Open:
Day 11 of 100 - Blackjack.ipynb
Run all cells.

Option 2: Run as Python Script (Optional)

If converted to a .py file:
python blackjack.py

🎮 How to Play

You are dealt two cards.
The dealer is dealt two cards (one hidden).

Choose to:

y → Draw another card (Hit)
n → Stop drawing cards (Stand)

The dealer draws until reaching at least 17.
Closest score to 21 without going over wins.
Blackjack Rules Implemented
Ace counts as 11 or 1 (automatically adjusted).
If you go over 21 → You bust.
If dealer goes over 21 → Dealer busts.
Blackjack (Ace + 10) wins automatically unless both have it.

📚 What I Learned

Functions and modular code structure
Working with lists
Randomization in Python
Game logic implementation
Handling edge cases (like Ace value adjustments)

🏁 Future Improvements

Add betting system
Add chip balance tracking
Create a GUI version
Improve UI formatting
Add multiplayer support

📜 License

This project is open-source and free to use.
