## Solve Sudoku


### Description

The solver is an executable R script called SolveSudoku located in the R subdirectory.

It solves Sudoku puzzles input as files. Each file consists of 9 lines matching the regex pattern:
    \[1-9\<X\>\]\(,\[1-9\<X\>\]\){8}
    Here, \<X\> is one of "", ".", "NA".

The Solver first checks the puzzle for errors. If none are found it outputs a solution to stdout.


### Usage 
SolveSudoku [-h] [-v] [-o output_file_name] puzzle_file


### Options

- h -- Help Message.
- v -- Verbose mode: Show recursions.
- o -- Place solution in an output file (comma separated).

### Args

- puzzle_file -- The name of a Sudoku Puzzle file.

### R Package Dependence
- Depends on the package(s): optparse. 

### Puzzles

Directory 'puzzles' contains of puzzles of varying difficulties as well as puzzles that are ill-formed which are used for testing.

