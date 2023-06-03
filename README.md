# Flappy Bird AI using NEAT

This project implements an AI agent to play the Flappy Bird game using the NEAT (NeuroEvolution of Augmenting Topologies) algorithm. The goal of the AI agent is to learn to navigate the bird through the gaps between pipes without colliding with them.

## Dependencies

To run this project, you need to have the following dependencies installed:

- Python 3.x
- Pygame
- NEAT-Python

## Installation

1. Install Python: Visit the official Python website (`https://www.python.org`) and download the latest version of Python for your operating system. Follow the installation instructions to complete the installation.

2. Install Pygame: Open a terminal or command prompt and run the following command to install Pygame using pip:

   ```
   pip install pygame
   ```

3. Install NEAT-Python: Open a terminal or command prompt and run the following command to install NEAT-Python using pip:

   ```
   pip install neat-python
   ```

## Running the Code

To run the Flappy Bird AI, follow these steps:

1. Clone the repository or download the source code files to your local machine.

2. Open a terminal or command prompt and navigate to the project directory.

3. Run the following command to execute the script:

   ```
   python flappy_bird_ai.py
   ```

4. The game window will open, and the AI agent will start learning to play Flappy Bird. The AI agent's performance and the current generation number will be displayed on the game window.

5. Once the AI agent has finished learning or you want to stop the program, you can close the game window or press Ctrl+C in the terminal or command prompt.

Note: The NEAT configuration file `config-feedforward.txt` is provided along with the source code. You can modify this file to adjust the NEAT parameters and experiment with different settings.

