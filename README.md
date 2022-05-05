# Artificial-Intelligence-and-Applications
My project scored 91% in the Artificial Intelligence and Applications module in year 2 (University of Exeter).  

Within this project, I focused on solving the 8-puzzle problem using the A* algorithm (using python). The second part of the project covered the implementation of the evolutionary algorithm (using python) to solve the Sudoku problem. The code was tested with three different sudoku grids and various population sizes: 10, 100, 1000, and 10000. After-which further experiments were then performed and analysed which helped produce the final report.

# GA Sudoku

Instructions for running the file GA_Sudoku.py program.

This program makes use of (EA) Genetic Algorithm to solve the Sudoku problem.
It contains multiple parameters which make be edited to suit different experiments.
These parameters are descibed below.

## Parameters
- GRID_FILE : Refers to the base grid file containing the Sudoku problem which you want to solve.
- NUMBER_GENERATION : Refers to the maximum number of generations that you wish to run the algorithm for.
- POPULATION_SIZE : Specifies the size of the individuals for a given generation.
- TRUNCATION_RATE : Specifies the number of individuals to be saved (in percentage).
- REPLACEMENT_RATE : Specifies the number of parents to be replaced in a given selection (in percentage).
- SUPER_MUTATE : Refers to the number of generations to be untouched before performing a super mutation. Use 0 to disable super mutations.
- TOLERANCE : Specify the tolerance leiency either side of the past generation to count as an untouched generations. E.g. SM Tolenerance = 1 would indicate gen1 = 3 then gen2 = 2, 3 or 4 would be untouched.
- TIME_MAX : Refers to the maximum time limit. Use 0 to disable time limit.
- VERBOSE : User can use VERBOSE to print details to the screen

Once the desired paramaters have been defined, run the program from the command line by typing 'GA_Sudoku.py'
## License

MIT
