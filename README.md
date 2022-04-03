# Lassoku

Lasso + Sudoku = Lassoku

Rules:
1. NxN grid
2. No subgrids
3. Numbers from 0-N (where N=length of grid)
4. A zero acts as a lasso and can be thrown by the number left or right to it
5. Throwing a lasso means "catching" the number N positions after the lasso where a number N resides
6. The result of catching a number is the sum of the current number N and the number that has been caught
7. All sums must sum up to a predefined row or column sum
