# Genetic Algorithm with Mutation and Crossover for New Generation Generation

This project implements a genetic algorithm in both Python and C++ to generate a new generation of solutions through a combination of mutation and crossover operations. Genetic algorithms are a powerful optimization technique inspired by the process of natural selection, allowing for the evolution of potential solutions to a problem over multiple generations.

## Table of Contents

- [Introduction](#introduction)
- [Algorithm Overview](#algorithm-overview)
- [Components](#components)
  - [Chromosome Representation](#chromosome-representation)
  - [Fitness Function](#fitness-function)
  - [Selection](#selection)
  - [Crossover](#crossover)
  - [Mutation](#mutation)
  - [Termination Condition](#termination-condition)
- [Usage](#usage)
  - [Python Implementation](#python-implementation)
  - [C++ Implementation](#cpp-implementation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Genetic algorithms are a subset of evolutionary algorithms that mimic the process of natural selection to evolve potential solutions to optimization and search problems. This project focuses on implementing a genetic algorithm with mutation and crossover functions to create a new generation of solutions iteratively.

## Languages  
<code>
<img align="center" src="https://github.com/devicons/devicon/blob/v2.15.1/icons/python/python-original-wordmark.svg" width="50" height="50" /> <img align="center" src="https://github.com/devicons/devicon/blob/v2.15.1/icons/vscode/vscode-original-wordmark.svg" width="50" height="50"/><img align="center" src="https://github.com/devicons/devicon/blob/v2.15.1/icons/numpy/numpy-original.svg" width="50" height="50"/><img align="center" src="https://github.com/devicons/devicon/blob/v2.15.1/icons/opencv/opencv-original-wordmark.svg" width="50" height="50" /> <img align="center" src="https://github.com/devicons/devicon/blob/v2.15.1/icons/pycharm/pycharm-original.svg" width="50" height="50"/>
</code>

## Algorithm Overview

1. Initialization: A population of potential solutions (chromosomes) is created randomly.

2. Evaluation: Each chromosome's fitness is evaluated using a user-defined fitness function that quantifies how well the chromosome solves the problem.

3. Selection: A subset of chromosomes is selected for reproduction based on their fitness. This subset is more likely to contain chromosomes that have higher fitness scores.

4. Crossover: Pairs of selected chromosomes undergo crossover, producing offspring with characteristics inherited from both parents.

5. Mutation: Some of the offspring's genes are subject to mutation, introducing small, random changes to diversify the population.

6. Termination: The process continues for a predetermined number of generations or until a termination condition is met (e.g., satisfactory solution found).

## Components

### Chromosome Representation

Chromosomes are represented as data structures containing genetic information. The structure of chromosomes should be defined based on the problem domain. For example, in a binary optimization problem, chromosomes can be represented as strings of 0s and 1s.

### Fitness Function

The fitness function quantifies the quality of a solution. It takes a chromosome as input and returns a fitness score that indicates how well the chromosome solves the problem. Higher fitness scores correspond to better solutions.

### Selection

Various selection strategies can be employed to choose chromosomes for reproduction. Common methods include tournament selection, roulette wheel selection, and rank-based selection.

### Crossover

Crossover involves combining genetic information from two parent chromosomes to produce one or more offspring. Different crossover techniques, such as one-point, two-point, or uniform crossover, can be applied based on the problem characteristics.

### Mutation

Mutation introduces small, random changes to individual genes within chromosomes. This helps maintain diversity in the population and prevents convergence to local optima.

### Termination Condition

The algorithm terminates when a specific condition is met, such as reaching a maximum number of generations or achieving a satisfactory solution.

## Usage

### Python Implementation

1. Install the required dependencies by running: pip install numpy

2. Run the Python script: python genetic_algorithm.py

3. Follow the on-screen instructions to provide necessary inputs and parameters.

### C++ Implementation

1. Compile the C++ code: g++ -o genetic_algorithm genetic_algorithm.cpp

2. Run the compiled executable: ./genetic_algorithm

3. Follow the prompts to input required parameters.

## Contributing

This is an open-source project and contributions are welcome. To contribute, please fork this repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Developers 👨🏻‍💻
<p align="center">
<a href="https://github.com/Awrsha"><img src="https://avatars.githubusercontent.com/u/89135083?v=4" width="100;" alt="Awrsha Parvizi"/><br /><sub><b>.:: Amir M. Parvizi ::.</b></sub></a>
</p>

## System & Hardware 🛠  
<br> <summary><b>⚙️ Things I use to get stuff done</b></summary> <ul> <li><b>OS:</b> Windows 11</li> <li><b>Laptop: </b>TUF Gaming</li> <li><b>Code Editor:</b> Visual Studio Code - The best editor out there.</li> <li><b>To Stay Updated:</b> Medium, Linkedin and Instagram.</li> <br /> ⚛️ Checkout Our VSCode Configrations <a href="">Here</a>. </ul> <p align="center">💙 If you like my projects, Give them ⭐ and Share it with friends!</p></p><p align="center"><img height="27" src="https://raw.githubusercontent.com/mayhemantt/mayhemantt/Update/svg/Bottom.svg" alt="Github Stats" /></p>

<p align="center">
<img src="https://raw.githubusercontent.com/mayhemantt/mayhemantt/Update/svg/Bottom.svg" alt="Github Stats" />
</p>
