# Computational Theory Module
#### Daniel Steshenko | G00380007
## Countdown Numbers Game

![Countdown Numbers Game](https://countdownnumbersgame.com/countdownimage.webp)
[Image Reference](https://countdownnumbersgame.com/)

This repository contains a Jupyter Notebook that delves into the computational analysis of the Countdown Numbers Game, a game from the television show "Countdown." This project focuses on dissecting various algorithmic strategies to solve the game, aiming to find a fast and efficient approach.

## Project Goals
The main objectives of this notebook are to:
- Explore computational challenges posed by the Countdown Numbers Game.
- Implement and compare different computational strategies for solving the game.
- Develop the `solve_numbers` function using efficient algorithmic approaches, also using Reverse Polish Notation (RPN).
- Assess and discuss the efficiency and computational complexity of the implemented strategies.

## Game Overview and Rules
- **Number Selection**: Players choose six numbers from two sets: one containing large numbers (25, 50, 75, 100) and another with small numbers (1-10).
- **Target Number**: A random target number is generated between 101 and 999.
- **Permitted Operations**: Players may use addition, subtraction, multiplication, and division to reach the target number. The operations must yield integer results, and each chosen number can only be used once.

## Computational Strategies and Methodologies
- **Algorithm Design**: Discusses the design of the `solve_numbers` function, which simulates different strategies to solve the game while adhering to its rules.
- **Reverse Polish Notation (RPN)**: Utilised to streamline the calculation process by simplifying the order of operations.

## Implementation Insights
- **`solve_numbers` Function**: Central to the notebook, this function outlines the step-by-step approach to finding solutions, explaining each decision and calculation in detail.
- **Random Number Simulation**: Describes how the numbers and target are generated to closely mimic the actual game conditions.
- **Efficiency and Validation**: Ensures that the computational strategies are not only correct but also optimised for performance, meeting the Countdown game's unique requirements.

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
   You can open the project files in any IDE like Visual Studio Code or in Jupyter Notebook if you prefer. To open the project in Jupyter Notebook, ensure you have Jupyter installed, and then run the following command from the project directory:
   ```bash
   jupyter notebook
   ```

## Using GitHub Codespaces

For those who prefer not to install software locally, GitHub Codespaces provides a cloud development environment accessible directly from your browser:

1. **Navigate to the GitHub Repository:**
    - Open the repository in your web browser.

2. **Start your Codespace:**
    - Go to the `Code` button and select `Codespaces`, and then select `Create codespace on main`.
    - A new tab will open in your browser, just wait for it to load and then move onto the next time.
3. **Run Jupyter Notebook:
    - Within Codespaces, open a terminal and type:
    ```bash
        gh cs jupyter
    ```
    - Select the current repository
    - Copy the token within the url, for example:
    ```bash
    http://localhost:46649/?token=COPY_TOKEN_FROM_HERE
    ```
    - You should see a pop-up on the left prompting you to open the app in your browser. Select `Open in browser`.
    - Paste the copied token in the password field. 
    - Select the notebook.