# Assignment 1: Dynamic Robot Movement Simulation 
This folder contains Jupyter notebook and report for the "Dynamic Robot Movement Simulation" project.

This Jupyter notebook demonstrates pathfinding algorithms, specifically A* and Uniform Cost Search (UCS), in a grid-based environment. 
The environment consists of a grid with obstacles where an agent needs to navigate from a starting position to a goal position while avoiding obstacles.

## Features

- Implementation of A* and Uniform Cost Search algorithms for pathfinding.
- Visualization of the grid, path, starting position, goal position, and charge stations.
- Generation of a random grid with specified size and obstacle probability.

## Requirements

- Python 3.x
- NumPy
- Matplotlib

## Files

- `CSE366_Assignment.ipynb`: The Jupyter notebook with the simulation implementation of pathfinding algorithms, environment setup, and visualization.
- `CSE366_Assignment1_Report.pdf`: A detailed report of the project.
- `README.md`: This file providing an overview of the notebook and instructions for usage.

## Running the Simulation

1. Ensure you have Jupyter Notebook and the required dependencies installed.
2. Run `CSE366_Assignment.ipynb`.
3. The script will generate a random grid, find paths using A* and UCS algorithms, and visualize the results.
4. The visualization includes the grid, start position (red square), goal position (green square), and charge stations (blue squares).
5. The script will print the solution paths, the number of charge stations encountered, and the charge points.


## Example

Here's an example of a generated grid with paths found using A* and UCS algorithms:

A* 

![A*](https://github.com/Rafsun-Islam/CSE-366-3--2021-3-60-024/assets/161591790/a4c30ceb-a28f-4edf-9fca-e8748ea97909)

UCS

![UCS](https://github.com/Rafsun-Islam/CSE-366-3--2021-3-60-024/assets/161591790/2d930aee-1057-4941-b7e2-c66aeab62c03)


