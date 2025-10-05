# Tom and Jerry Maze Search Algorithms

This project implements various **search algorithms** to navigate a maze in the **Tom and Jerry** game, with the goal of finding the shortest path for Tom to catch Jerry.

## Objective

The goal of this project is to simulate Tom trying to catch Jerry in a maze-like environment. The maze consists of **movable spaces** and **walls**. The algorithms aim to find the most efficient path for Tom to reach Jerry while avoiding obstacles. The project uses the following search algorithms:

### **Algorithms Implemented:**

1. **Breadth-First Search (BFS)**:  
   - Explores the maze level by level, ensuring that the shortest path is found.
   - BFS is **unweighted** and guarantees the shortest path for unweighted graphs.

2. **Uniform Cost Search (UCS)**:  
   - Similar to BFS but accounts for the cost of each move. This ensures the path found is the least costly.
   - UCS is useful when there are varying costs associated with different cells.

3. **Greedy Best-First Search**:  
   - A heuristic-based search that expands nodes closer to the goal, aiming to find a solution quickly.
   - Does not guarantee the shortest path but can be faster than BFS in some cases.

4. **A* Search**:  
   - Combines the advantages of both BFS and Greedy search by considering both the **cost to reach** the node and **heuristic estimates** to the goal.
   - A* is the most efficient and commonly used algorithm for pathfinding.

## Features

- **Maze Generation**: A grid-based maze with walls (brown cells) and empty spaces (white cells).
- **Multiple Search Algorithms**: Includes BFS, UCS, Greedy, and A* to compare their efficiency in finding the shortest path.
- **Visualization**: Displays the maze with Tom’s and Jerry’s positions and the path taken by the algorithm.
- **User Input**: Users can set the start and end points (Tom’s and Jerry’s positions) and choose the algorithm for the search.

## How to Run the Project

1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/sahellsabetii/TomJerry.git
    ```

2. Navigate into the project folder:
    ```bash
    cd TomJerry
    ```

3. Compile the code (if necessary, depending on the programming language used):
    ```bash
    make
    ```

4. Run the program:
    ```bash
    ./tomjerry
    ```

5. Select the algorithm you want to use and input the maze details (start and goal positions).

## Example

- **Start**: Tom's position at (1,1)
- **Goal**: Jerry's position at (5,5)

You can test the maze with different start and goal points, and compare the paths found by each algorithm.

## Technologies Used

- **Programming Language**: C / Python (or whichever language you used)
- **Algorithms**: BFS, UCS, Greedy, A*
- **Tools**: [Any libraries or frameworks you used for visualization, if applicable]

## License

This project is open source and available under the MIT License. Feel free to use, modify, and distribute it.

## Contact

- GitHub: [sahellsabetii](https://github.com/sahellsabetii)
- Email: [Sabetisahel@gmail.com](mailto:Sabetisahel@gmail.com)
