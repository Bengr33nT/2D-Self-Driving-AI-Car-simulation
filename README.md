# 2D Self-Driving Car Simulation

## Overview

This project is a self-driving car simulation built using Python, NEAT (Neuroevolution of Augmenting Topologies), and Pygame. The simulation features virtual cars that navigate a map, making real-time decisions based on sensor inputs to avoid collisions and optimize their driving paths.

## Features

- **Neural Network Control**: Each car is controlled by a neural network that evolves over generations to improve performance.
- **Collision Detection**: Cars use radars to detect obstacles and adjust their movements accordingly.
- **Dynamic Simulation**: Visual representation of the simulation in real-time using Pygame.

## Technologies Used

- Python
- Pygame
- NEAT (Neuroevolution of Augmenting Topologies)

## Getting Started

### Prerequisites

- Python 3.x
- Pygame library
- NEAT-Python library

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/self-driving-car-simulation.git
    cd self-driving-car-simulation
    ```

2. Install the required libraries:
    ```bash
    pip install pygame neat-python
    ```

### Running the Simulation

1. Ensure you have the necessary image files (`car.png` and `map.png`) in the project directory.
2. Run the simulation:
    ```bash
    python main.py
    ```

## How It Works

- The simulation initializes a population of cars, each with its own neural network.
- Each car uses distance data from radars to make driving decisions (turning, accelerating, or decelerating).
- The fitness of each car is evaluated based on the distance traveled, allowing the NEAT algorithm to evolve better-performing networks over generations.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

## Acknowledgments

Inspired by Cheesy AI and optimized with contributions from the community.
