## Autonomous Delivery Robot with A* Search Algorithm
This project simulates an autonomous delivery robot navigating a city grid to deliver items to randomly assigned locations. The robot avoids obstacles like buildings, houses, and vehicles on roads using informed search algorithms, particularly the A* algorithm, to find the optimal path. The environment is dynamic, with obstacles and delivery points changing after each successful delivery.

## Features
City Environment Representation: The city grid is visualized as a 15x15 grid where obstacles like buildings and vehicles are placed, and delivery locations are randomly generated.
Search Algorithms: The robot uses the A* search algorithm for pathfinding, with comparisons made against the best-first search algorithm. A heuristic based on Euclidean distance is used to calculate the distance to the goal.
Dynamic Environment: After each delivery, the environment updates dynamically with changing start and goal positions, simulating real-world scenarios.
Real-Time Path Execution: The robot follows the planned path in real-time, avoiding collisions and recalculating paths if the environment changes.
Visualization: The robot's path, obstacles, and delivery points are visualized using matplotlib or pygame for interactive simulation.
Multiple Deliveries: The robot makes 5 sequential deliveries, adapting its path after each delivery. Each new delivery starts at the previous delivery location.
## Project Structure
Algorithm Implementation: The A* search algorithm is implemented, using a heuristic based on Euclidean distance and dynamic cost updates between 1 to 20. The robot replans paths in real-time based on changes in the environment.

Environment Simulation: A 15x15 grid represents the environment, including obstacles, start and goal points, and vehicles. This is visualized with libraries like matplotlib or pygame.

Graphical User Interface (GUI): The GUI allows users to interact with the simulation, view the robot's path, and observe dynamic changes in real-time. The GUI is created using Python libraries such as pygame, Tkinter, or PyQt.
