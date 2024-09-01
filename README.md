# Maze Algorithm

This project contains an algorithm that helps you navigate a maze map from the starting point to the destination. It also provides detailed information on how the code works and which functions are used.


https://github.com/erdemserhat/mazeAlgorithm/assets/116950260/9b5a605e-915c-45fd-9764-7bc4445031cf

![1a](https://github.com/user-attachments/assets/c3753ab9-a27d-407d-bba6-9ca5e462618e)




## Algorithm Overview

The project consists of the following key components:

- A 2D character array called `matrix` representing the maze map.
- Another character array named `roadOutLine` to store the solution path.
- The "labirent.txt" file containing a text of 20 lines, with each line having 20 characters.
- The `pathValidator` function, which is the main function responsible for solving the maze.
- The `appearanceShaper` function, which formats the appearance of the maze.
- The `doorValidator` function, which checks if a cell is a valid door.

The algorithm starts with the `pathValidator` function. This function traverses the maze map starting from the initial point and tries to reach the destination. At each step, the `doorValidator` function is used to check whether a valid path is being followed. As the path is followed, an "x" symbol is placed on the map to leave a trace, and the solution path is built.

The most important point to note is that the `pathValidator` function can call itself recursively. This allows different paths to be explored in different directions. If a path is found that reaches the number 9, the maze is considered solved.

This project offers an opportunity to understand the working logic of this algorithm and customize it according to your needs.

## Usage

1. Create or edit the maze map in the "labirent.txt" file. Each character's meaning is as follows:
   - '0': A wall
   - '1': A valid path
   - '9': The destination point

2. Run the Java program and observe the maze being solved.
