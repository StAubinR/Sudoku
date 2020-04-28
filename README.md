# Sudoku
Sudoku Webpage to help, solve, validate, create and teach with algorithms (naked and hidden n pairs, intersection, xwing)

You can try it here: https://staubinr.github.io/Sudoku/SudokuWP.html

This is just one html page under 1000 lines with javascript to test algorithms to solve Sudoku puzzles like humans do.  I tried to keep things as simple as possible without any fancy javascript stuff.  I tried to focus on algorthms that people can use to solve a puzzle.  If anybody has more fun coding a Sudoko Puzzle than to solve one, let me know.

This program has the following options:
1) Clear Board: Empty Sudoku Grid before you enter your own Sudoku.
2) Hide/Show candidates: Show normal candidates in black and candidates removed with strategies are in red.
3) Validate a Sudoku Puzzle: Count how many solutions you have.
4) New Easy: Create/generate a new easy to solve sudoku puzzle, without using any strategies.
5) New Hard: Create/generate a new hard to solve Sudoku puzzle, using naked and hidden pairs only.
6) Show/Hide Tips: Show how to solve a Sudoku.
7) Load Board: Cut/paste a string to create your sudoku grid.

This javascript program contains three major functions to eliminate candidates:
1) findn: find naked and hidden n pair.  "n pair" here can be 2, 3, .. n number.
2) findblc: find block, line column that intersect.
3) findxwn: find xwing with n column/line, like swordfish and jelly fish.

I expect to add more strategies one day if someone is interested.
