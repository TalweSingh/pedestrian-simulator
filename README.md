## Pedestrian simulator

This is a pedestrian simulator that simulates the movement of pedestrians in a given environment. 
The environment is represented by a grid, where each cell can be either empty or occupied by a 
pedestrian/obstacle. Pedestrians move in the grid according to a path planning algorithm that 
avoids collisions (e.g. Dijkstra).
The simulator is implemented in Python and uses the Pygame library for visualization. 
Environments can be loaded from a json file.
