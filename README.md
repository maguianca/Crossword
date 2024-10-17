# Crossword Puzzle
This project is a Crossword Puzzle Generator and Solver built using constraint satisfaction techniques. The goal is to fill in the blank cells of a crossword puzzle with words from a predefined list, ensuring all words fit properly and any overlapping words share the same characters in intersecting cells.
# Features
- Generates a crossword puzzle layout from a structure file.  
- Solves the puzzle by filling it with words from a list.  
- Uses Constraint Satisfaction Problem (CSP) techniques to solve the puzzle:  
    - Node Consistency  
    - Arc Consistency (AC-3 Algorithm)  
    - Backtracking with Least Constraining Value and Minimum Remaining Values heuristics  
- Prints the crossword solution to the terminal or saves it as an image file.  
![output](https://github.com/user-attachments/assets/0f0f5da9-96a4-429e-b65d-0689694ed9b9)

# Key Concepts
This crossword generator and solver use the principles of Constraint Satisfaction Problems (CSP), which involves:  

**Node Consistency**: Ensures that each word assigned to a variable fits the length required by the crossword grid.  
**Arc Consistency:** Ensures that overlapping words in the crossword share consistent letters in their intersecting cells (AC-3 Algorithm).  
**Backtracking Search:** Attempts to assign words to the puzzle incrementally, using heuristics to improve efficiency:  
**Minimum Remaining Values (MRV):** Prioritizes variables (empty spaces in the crossword) that have the fewest legal word choices left.  
**Least Constraining Value (LCV):** Orders the possible word choices by how few conflicts they cause for neighboring variables.  

# License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
