# Flappy Bird NEAT AI

## Overview

This project is a Flappy Bird game implemented using Python and Pygame, enhanced with NEAT (NeuroEvolution of Augmenting Topologies) to train an AI to play the game. The AI learns to navigate through pipes and achieve the highest score possible using a neural network.

## Installation

### Prerequisites

- Python 3.6 or later
- Pygame
- NEAT-Python

### Setup

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/flappy-bird-neat.git
    cd flappy-bird-neat
    ```

2. **Install Dependencies**

    Create a virtual environment (optional but recommended):

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

    Install the required packages:

    ```bash
    pip install pygame neat-python
    ```

3. **Download Assets**

    Make sure to have the images required for the game. Place them in a folder named `imgs` within the project directory. The required images are:
    - `pipe.png`
    - `bg.png`
    - `bird1.png`
    - `bird2.png`
    - `bird3.png`
    - `base.png`

4. **Configure NEAT**

    Ensure you have a NEAT configuration file named `ConfigFeedForward.txt` in the project directory. You can modify or create this configuration file based on your NEAT setup.

## Usage

1. **Run the Simulation**

    Execute the main script to start the simulation:

    ```bash
    python FlappyBird.py
    ```

    This will train the AI to play Flappy Bird using the NEAT algorithm. The AI's performance will improve over generations.

2. **View Results**

    The script will output the progress of the simulation in the terminal, including the best genome's fitness and statistics.

## Gameplay Controls

- **No controls needed:** The AI automatically learns to play the game through training.

## Configuration

To modify the NEAT parameters, edit the `ConfigFeedForward.txt` file. This file controls the neural network's configuration, including population size, mutation rates, and more.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a Pull Request for review.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Pygame](https://www.pygame.org/) - For the game development framework.
- [NEAT-Python](https://neat-python.readthedocs.io/en/latest/) - For the NEAT algorithm implementation.
- [Flappy Bird](https://en.wikipedia.org/wiki/Flappy_Bird) - For the game inspiration.

---

Feel free to customize the sections to better fit your project's needs and specifics. Ensure all paths and URLs are correct, and adjust instructions based on your development environment.
