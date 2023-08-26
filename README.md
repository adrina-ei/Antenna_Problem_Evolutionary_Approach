<h1>
<br>Antenna_Problem_Evolutionary_Approach
</h1>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [📂 Project Structure](#-project-structure)
- [🔎 Details of Codes](#-details-of-codes)
- [🚀 Getting Started](#-getting-started)
- [📝 Results](#-results)
- [🤝 Collaborators](#-collaborators)


---
## 📍 Overview

This repository contains an evolutionary approach to solving the Antenna Problem. The Antenna Problem involves finding the optimal configuration and placement of a set of antennas to achieve maximum users' satisfaction (Internet signal and speed in this case) in a given area. The goal of this project is to apply evolutionary algorithms to find a solution that maximizes the users' satisfaction while considering various constraints.
Evolutionary algorithms mimic the process of natural selection to find an optimal solution within a given search space. By evolving a population of candidate antenna configurations over multiple generations, we can gradually converge towards an optimal solution.

---


## 📂 Project Structure

 * [README.md](./README.md)
 * [Codes](./Codes)
   * [data](./Codes/data)
     * [blocks_population.txt](./Codes/data/blocks_population.txt)
     * [problem_config.txt](./Codes/data/problem_config.txt)
   * [chart.ipynb](./Codes/chart.ipynb)
   * [code.ipynb](./Codes/code.ipynb)
   * [requirements.txt](./Codes/requirements.txt)
 * [Documents](./Documents)
   * [logs](./Documents/logs)
     * [log_0.1_0.1.txt](./Documents/logs/log_0.1_0.1.txt)
     * [log_0.1_0.9.txt](./Documents/logs/log_0.1_0.9.txt)
     * [log_0.9_0.1.txt](./Documents/logs/log_0.9_0.1.txt)
     * [log_0.9_0.9.txt](./Documents/logs/log_0.9_0.9.txt)
     * [plot_0.1_0.1.png](./Documents/logs/plot_0.1_0.1.png)
     * [plot_0.1_0.9.png](./Documents/logs/plot_0.1_0.9.png)
     * [plot_0.9_0.1.png](./Documents/logs/plot_0.9_0.1.png)
     * [plot_0.9_0.9.png](./Documents/logs/plot_0.9_0.9.png)
   * [Persian_Doc.pdf](./Documents/Persian_Doc.pdf)
   * [Problem Statement.pdf](./Documents/Problem%20Statement.pdf)
   
---

## 🔎 Details of Codes

### [Code](./Codes/code.ipynb)
The evolutionary algorithm implemented in this file follows a standard genetic algorithm framework. It involves the following steps:

1. **Initialization**: Generate an initial population of candidate antenna configurations randomly.

2. **Evaluation**: Evaluate each antenna configuration's fitness based on the users' satisfaction achieved and consider any constraints.

3. **Selection**: Select a subset of the population for reproduction based on their fitness. Better-performing solutions have a higher chance of being selected.

4. **Crossover**: Create new offsprings by combining the genetic material (parameters) of selected individuals.

5. **Mutation**: Introduce random changes in the offspring's genetic material to explore new areas of the search space.

6. **Replacement**: Replace some individuals in the population with the new offspring.

7. **Termination**: Check termination conditions, such as reaching a maximum number of generations or finding a satisfactory solution.

8. Repeat steps 2-7 until the termination conditions are met.


### [Chart](./Codes/chart.ipynb)
This code visualizes the best results of the evolutionary approach applied to the antenna problem.

---
## 🚀 Getting Started

### ✔️ Requirements

Before you begin, ensure that you have the packages in `requirements.txt` installed.

### 📦 Installation

1. Clone the Antenna_Problem_Evolutionary_Approach repository:
```sh
https://github.com/audrina-ebrahimi/Antenna_Problem_Evolutionary_Approach.git
```

2. Change to the project directory:
```sh
cd Antenna_Problem_Evolutionary_Approach
```

3. Install the dependencies:
```sh
pip install -r ./Codes/requirements.txt
```

### 🎮 Using Antenna_Problem_Evolutionary_Approach

* Once the installation is complete, you can run the evolutionary algorithm to solve the Antenna Problem. Follow these steps:

* Prepare the input data: The input data should include the blocks to be covered and their population. You can find it in [blocks_population.txt](./Codes/data/blocks_population.txt).

* Configure the algorithm parameters: You may need to set parameters such as the tower construction cost, tower maintanance cost, user satisfaction levels, and user satisfaction scores. You can find it in [problem_config.txt](./Codes/data/problem_config.txt).

* Run the algorithm.

* Analyze the results: Once the algorithm finishes, the best antenna configuration found will be displayed.

---

## 📝 Results

The results of running the code with different config for evolutionary algorithm can be found in the [logs](./Documents/logs) directory. This directory contains logs and plots which helps analyze the performance and quality of the solution found.

---
## 🤝 Collaborators
[Kian Majlessi](https://github.com/kianmajl) and [Audrina Ebrahimi](https://github.com/audrina-ebrahimi)
