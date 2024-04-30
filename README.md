# Computational Theory Module
#### Daniel Steshenko | G00380007
## Countdown Numbers Game

![Countdown Numbers Game](https://countdownnumbersgame.com/countdownimage.webp)
[Image Reference](https://countdownnumbersgame.com/)

This repository contains a Jupyter Notebook that delves into the computational analysis of the Countdown Numbers Game, a game from the television show "Countdown." This project focuses on dissecting various algorithmic strategies to solve the game, aiming to find a fast and efficient approach.

## Countdown Game Rules

- Participants are given six numbers from two pools: one pool, which consists of any of the following numbers: 25, 50, 75, 100 and the second pool, which consists of numbers between 1 to 10.
- Participants are then given a target number between 101 and 999.
- Participants can use addition, subtraction, multiplication, and division.
- The goal is to reach the target number using the given numbers and operations.
- The Operations must return integer results.
- Each number can only be used once per game.
- Whichever participant reaches the target number or is the closest wins the game.

## Project Objectives
- Investigate the challenges found in the Countdown Numbers Game.
- To effectively solve the game, develop, implement, and evaluate different algorithms, including brute-force, heuristic algorithms, and dynamic programming approaches.
- To explore various computational strategies, Using the `solve_numbers` function and `solve_numbers_ha_rpn` that uses Heurtistic Algorithms with Reverse Polish Notation and `solve_numbers_dp` for dynamic programming.
- Review the efficiency and computational complexity of each method used.

## Approaches
- `solve_numbers` **(Brute Force Approach):** Describes the brute-force method where every possible combination of numbers and operations is tested to find a solution to the target number.
- `solve_numbers_ha_rpn` **(Heuristic Algorithms with RPN):** This function applies heuristic algorithms alongside Reverse Polish Notation to efficiently manage and simplify the calculation order.
- `solve_numbers_dp` **(Dynamic Programming):** Details the dynamic programming strategy used to break down the problem into manageable subproblems, solving them incrementally to optimise performance.

## Notebook

- Countdown Numbers Game Notebook [View Notebook](https://github.com/DanielSteshenko/computational-theory/blob/main/countdown.ipynb)

## Prerequisites

To run the notebook effectively, ensure you have the following installed:

1. [Git](https://git-scm.com/downloads) - For cloning the repository.
2. [Python 3.x & Pip](https://www.python.org/downloads/) - For running the Python code.
3. [Jupyter Notebook](https://jupyter.org/install) or any IDE like [Visual Studio Code](https://code.visualstudio.com/download) - For interacting with the notebook.

## Getting Started

Follow these steps to run this repository on your machine:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/DanielSteshenko/computational-theory.git
   ```
2. **Navigate to the cloned directory:**
   ```bash
   cd computational-theory
   ```
3. **Open the project in an IDE or Jupyter Notebook**
   You can open the project files in any IDE, like Visual Studio Code or Jupyter Notebook. To open the project in Jupyter Notebook, ensure you have Jupyter installed, and then run the following command from the project directory:
   ```bash
   jupyter notebook
   ```

## Using GitHub Codespaces

For those who prefer not to install software locally, GitHub Codespaces provides a cloud development environment accessible directly from your browser:

1. **Navigate to the GitHub Repository:**
    - Open the repository in your web browser.

2. **Start your Codespace:**
    - Go to the `Code` button, select `Codespaces`, and then select `Create codespace on main`.
    - A new tab will open in your browser; just wait for it to load and then move on the next time.
3. **Run Jupyter Notebook:
    - Within Codespaces, open a terminal and type:
    ```bash
        gh cs jupyter
    ```
    - Select the current repository
    - Copy the token within the URL, for example:
    ```bash
    http://localhost:46649/?token=COPY_TOKEN_FROM_HERE
    ```
    - You should see a pop-up on the left prompting you to open the app in your browser. Select `Open in browser`.
    - Paste the copied token in the password field. 
    - Select the notebook.
