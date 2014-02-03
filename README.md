The input to Sudoku is a 9x9 board that is subdivided into 3x3 squares. Each cell is either blank or contains an integer from 1 to 9. A solution to a puzzle is the same board with every blank cell filled in with a digit from 1 to 9 such that every digit appears exactly once in every row, column and square. The input to the program is a text file containing a collection of Sudoku boards, with one board per line. For each board that is read, the output is a printout of the board correctly filled in.

We were given a 'board' class with some pre-defined declarations and definitions, however we had to add functionality to:
1. initialize the board, and update conflicts,
2. print the board and the conflicts to the screen,
3. check whether a value causes conflicts if it is placed in a cell,
4. add a value to a cell, and update conflicts,
5. clear a cell, and update conflicts, and
6. check to see if the board has been solved (return true or false, and print the result to the screen)