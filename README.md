# Rock, Paper, Scissors Challenge

## Project Overview
This project implements a program to play **Rock, Paper, Scissors** against four different AI bots (`quincy`, `abbey`, `kris`, `mrugesh`).  
The goal is to design a **smart player** that wins at least 60% of the games against each bot. Random play will usually win only ~50% of the time.

The project is built using the **Ona starter code** and consists of four main files:
- `main.py` – Entry point for testing and running unit tests.
- `RPS_game.py` – Game engine with bot implementations (do not modify this file).
- `RPS.py` – Custom `player()` function where you implement your strategy.
- `test_module.py` – Unit tests to validate that your player defeats each bot ≥60%.

---

## How to Run

### 1. Test Against Bots Interactively
You can play a manual game against a bot by uncommenting in `main.py`:

```python
play(human, abbey, 20, verbose=True)
play(human, random_player, 1000, verbose=True)
