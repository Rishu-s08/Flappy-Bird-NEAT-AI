# Flappy Bird NEAT AI

This repository contains an implementation of a neuroevolutionary algorithm, NEAT (NeuroEvolution of Augmenting Topologies), in Python to train an AI agent to play the popular game Flappy Bird. NEAT is a powerful technique that evolves artificial neural networks (ANNs) with genetic algorithms, allowing the agent to learn and improve its gameplay over time.

![Flappy Bird NEAT AI](flappy_bird_neat.gif)

## Features

 - NEAT implementation: Utilizes the NEAT algorithm to train and evolve the AI agent's neural network.
 - Flappy Bird game environment: Provides an accurate reproduction of the Flappy Bird game for the AI agent to interact with and learn from.
 - Pygame integration: Uses Pygame library to handle game graphics, inputs, and sound.
 - Neural network evolution: The AI agent's neural network structure evolves dynamically to optimize its ability to navigate the game.
 - Fitness evaluation: Each neural network's fitness is evaluated based on its performance in the game, encouraging the AI agent to learn and improve.
 - Visualization: Real-time visualization of the AI agent's gameplay and learning progress.

## Requirements

- Python 3.7 or above
- NEAT-Python library
- Pygame library

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Rishu-s08/Flappy-Bird-NEAT-AI
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the training script:
   ```bash
   python flappybird.py
   ```

4. Observe the AI agent's progress in the game and its learning process through the visualization provided.
5. Customize the NEAT parameters and game environment settings as desired to experiment with different training configurations.


## Customization

You can customize the AI training by modifying the NEAT parameters in the `neat-feedforward.txt` file. Adjusting parameters such as population size, mutation rates, and species compatibility threshold can affect the learning behavior.

## Contributions

Contributions to this repository are welcome. Feel free to open issues or submit pull requests to enhance the project.

## Acknowledgments

This project is inspired by the original Flappy Bird game by Dong Nguyen and is built upon the NEAT algorithm implementation by Kenneth O. Stanley and Risto Miikkulainen.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

Enjoy watching an AI agent master Flappy Bird using NEAT!
