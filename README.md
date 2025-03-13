# SnakeCubeSolver
Recursive Algorithm for solving the 5x5 SnakeCube Puzzle

## Description
The Snakecube Puzzle is a 5x5 puzzle that is composed of straight (S) pieces and bend (B) pieces.
This particular cube is represented as:
SBSSBBBBBBBBBBSBBSSBBBBSSBSBBBBBBSBSBBBBBBBBBSBBSBBSBBSSBBBSBBSS
and the solution is composed of right (R), left (L), front(F), back (B), up (U), and down (D) orientations of each cube and is represented as:
RBBBLURFLDFUFRRDBBBURDFFFUUBDBLULLFFURDRURBLDDLUULBBDRRRFULLBRRR

The algorithm for finding the solution is a Depth-First-Search (DFS) recursion and finds all possible solutions.

## Run Solver
python snakecube_solver.py

## Run Animator
manim -pqh snakecube_animation.py SnakeCubeVisualization


![snake_cube](https://github.com/user-attachments/assets/a8703e8b-70c0-49ef-95ee-4de2c07e6ae0)


https://github.com/user-attachments/assets/c1e389f4-f906-46ed-abb1-a6062d83094b

