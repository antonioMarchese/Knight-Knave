# Knights and Knaves Logic Puzzle Solver

This project provides a solver for the Knights and Knaves logic puzzles using propositional logic. In these puzzles, each character is either a knight (who always tells the truth) or a knave (who always lies). The objective is to determine the type of each character based on their statements.

## Project Structure
* logic.py: This file contains the necessary logic for creating and manipulating propositional symbols and formulas.
* puzzle.py: This is the main script that defines the puzzles and checks the solutions.

## Puzzles
### Puzzle 0
* A says: "I am both a knight and a knave."
* Solution: Determine if A is a knight or a knave.
  
### Puzzle 1
* A says: "We are both knaves."
* Solution: Determine the types of A and B.

### Puzzle 2
* A says: "We are the same kind."
* B says: "We are of different kinds."
* Solution: Determine the types of A and B.

### Puzzle 3
* A says: Either "I am a knight." or "I am a knave.", but you don't know which.
* B says: "A said 'I am a knave'."
* B says: "C is a knave."
* C says: "A is a knight."
* Solution: Determine the types of A, B, and C.

## How to Use
1. Prerequisites: Ensure you have Python installed on your machine.
2. Clone the repository: Clone this repository to your local machine using git clone.
3. Run the solver: Execute the main script by running the following command in your terminal:
``` python puzzle.py ```

The script will output the type of each character (whether they are a knight or a knave) for each puzzle.

## Adding New Puzzles
To add new puzzles, define the puzzle's knowledge in a similar format to the existing ones in puzzle.py, and add it to the puzzles list.
