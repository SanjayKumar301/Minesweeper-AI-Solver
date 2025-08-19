# Minesweeper-AI-SolverThis project develops an intelligent AI agent to solve the classic game of Minesweeper. The AI is designed to autonomously navigate a Minesweeper board, using logical deduction to identify safe cells and mines. In scenarios where pure logic is not enough, the agent employs probabilistic reasoning to make calculated guesses.

The project is structured in two parts to demonstrate a comprehensive understanding of AI principles:

AI Logic on a Simulated Board: This phase focuses on the core AI algorithms, including knowledge representation, logical inference, and probabilistic guessing. This part of the project provides a clean environment to test and refine the AI's decision-making process without the complexities of a real-world interface.

Automated Web Solver: This advanced phase extends the AI to interact with a live Minesweeper game on a website (e.g., "Minesweeper Online"). This requires integrating computer vision to interpret the game state from screenshots and mouse automation to perform actions on the board.

🧠 Core AI Principles Applied
Knowledge Representation: The AI maintains a digital representation of the board, tracking the state of each cell (e.g., covered, revealed, flagged).

Logical Reasoning: The agent applies a set of rules to deduce the location of mines and safe squares. This involves identifying clear cases where a number's value perfectly matches the number of surrounding covered or flagged cells.

Sentence-Based Logic: For more complex situations, the AI models board segments as logical sentences (e.g., "A+B+C=2") and solves them to uncover new information.

Probabilistic AI: When no logical move is available, the AI calculates the probability of each unknown cell being a mine and chooses the one with the lowest risk.

🚀 Getting Started
Prerequisites
To run this project, you'll need the following installed:

Python 3.x

The required Python libraries (list them here). You can install them using pip.

Bash

pip install -r requirements.txt
Installation
Clone this repository to your local machine:

Bash

git clone https://github.com/[Your-Username]/Minesweeper-AI-Solver.git
Navigate to the project directory:

Bash

cd Minesweeper-AI-Solver
Install the required packages:

Bash

pip install -r requirements.txt
How to Run
To run the simulated board solver:

Bash

python main_simulator.py
To run the web solver (for "Minesweeper Online"):

Bash

python main_web_solver.py
Note: Ensure the game window is visible and properly positioned on your screen for the AI to interact with it.

📂 Project Structure
main_simulator.py: Contains the code for the AI logic and the simulated game board.

main_web_solver.py: Contains the code for screen capture, image recognition, and mouse automation to interact with the web game.

solver/: A directory containing the core AI logic, including logic.py and probabilistic.py.

utils/: A directory for utility functions, such as image processing and mouse control.

requirements.txt: Lists all the necessary Python libraries.

🤝 Contribution
Contributions are what make the open-source community such a fantastic place to learn and create. Any contributions you make are greatly appreciated.

Fork the Project

Create your Feature Branch (git checkout -b feature/AmazingFeature)

Commit your Changes (git commit -m 'Add some AmazingFeature')

Push to the Branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
Distributed under the MIT License. See LICENSE for more information.


Project Link: https://github.com/Your-Username/Minesweeper-AI-Solver
