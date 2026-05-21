# 🎮 Minesweeper AI Game

An interactive, graphical **Minesweeper** game built with Python and Pygame, featuring an autonomous **Artificial Intelligence (AI)** player that can solve the game logically using propositional logic and inference.

---

## ✨ Features
* **Play Yourself:** Play the classic Minesweeper game manually using mouse clicks.
* **AI Autonomous Play:** Click the **"AI Move"** button to watch the AI engine analyze the board, place flags safely, and make logical moves to win.
* **Knowledge-Based AI:** The AI uses a knowledge base of logical sentences to infer safe cells and pinpoint mines with 100% accuracy based on available data.

---

## 🚀 Getting Started & Installation

Follow these steps to get the game up and running on your local machine.

### 1. Prerequisites
Make sure you have **Python 3.12** installed on your system. 

### 2. Install Dependencies
This project requires the `pygame` library. Install it using the standard terminal:

```bash
py -3.12 -m pip install pygame




🎮 How to Run the Game
Once the installation is complete, run the graphical interface by executing the following command in your terminal:

Bash
py -3.12 runner.py
🕹️ How to Play:
Click Play Game to start a new match.

Left-click on any cell to reveal it.

Right-click to place a red flag on suspected mines.

Click AI Move at any time to let the AI make a calculated, logical move for you!

🛠️ Project Structure
minesweeper.py: Contains all the logical components of the game, including the Sentence class and the MinesweeperAI agent.

runner.py: Handles the graphical user interface (GUI) and rendering using Pygame.

assets/: Contains fonts and images used for the game visuals
