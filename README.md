# 🤖 Rock Paper Scissors - AI Project

This project implements an AI-powered Rock Paper Scissors game, designed to adapt and counter various opponents by analyzing move history and predicting future plays. Built as part of the [freeCodeCamp Machine Learning with Python certification](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/rock-paper-scissors), it demonstrates prediction logic and algorithmic strategy.

## 📂 Project Structure

- `RPS.py`: Your custom AI player logic.
- `RPS_game.py`: Contains the game engine and built-in bots (`quincy`, `abbey`, `kris`, `mrugesh`, `random_player`).
- `main.py`: Runs the game between your AI and the built-in bots.
- `test_module.py`: Unit tests to ensure your AI wins at least 60% of games against each bot.
- `.gitignore`: Prevents Python cache files from being committed.

## 🚀 How to Run

1. **Install Python** (if not already):  
   Make sure Python 3.6+ is installed.

2. **Run the Game Simulation:**
   ```bash
   python main.py
   ```

3. **Run Unit Tests:**
   ```bash
   python test_module.py
   ```

## 🧠 AI Strategy

The AI (`player` function in `RPS.py`) learns by recognizing repeating 4-move patterns from the opponent’s history and counters the predicted next move accordingly.

## 🕹️ Built-in Bots

- `quincy`: Repeats a fixed sequence.
- `abbey`: Tracks opponent's last two moves and adapts.
- `kris`: Always counters the last move.
- `mrugesh`: Uses frequency analysis over last 10 moves.
- `random_player`: Chooses randomly.
- `human`: Accepts player input from the command line.

## ✅ Goals

Your AI must beat each bot **at least 60% of the time over 1000 games**. This is enforced via `test_module.py`.

---

Made with 💡 and Python 🐍.
