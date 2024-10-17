# Crossword Puzzle
This project is a Crossword Puzzle Generator and Solver built using constraint satisfaction techniques. The goal is to fill in the blank cells of a crossword puzzle with words from a predefined list, ensuring all words fit properly and any overlapping words share the same characters in intersecting cells.
# Features
#Generates a crossword puzzle layout from a structure file.
Solves the puzzle by filling it with words from a list.
Uses Constraint Satisfaction Problem (CSP) techniques to solve the puzzle:
Node Consistency
Arc Consistency (AC-3 Algorithm)
Backtracking with Least Constraining Value and Minimum Remaining Values heuristics
Prints the crossword solution to the terminal or saves it as an image file.
