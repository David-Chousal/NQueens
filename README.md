# N-Queens Problem Solver

This project provides a C implementation to solve the classic N-Queens problem, which asks: "How can you place N queens on an N×N chessboard so that no two queens threaten each other?"

## How the Program Works

- The program uses a recursive backtracking algorithm to find all possible solutions for the N-Queens problem.
- For each solution, it prints the board to the console, marking queens with `Q`, and using `.` and spaces for other cells for visual clarity.
- The number of solutions found is also displayed.

## Usage Instructions

### 1. Compile the Program

Use `gcc` to compile the source code:

```bash
gcc -o nqueens NQUEENS.c
```

### 2. Run the Program

You can specify the size of the board (N) as a command-line argument. If no argument is given, it defaults to 8 (the classic 8-queens problem).

```bash
./nqueens 8
```

Replace `8` with any positive integer to solve for a different board size.

### Example Output

```
No. 1
-----
Q . . . . . . .
. . . . Q . . .
. . . . . . . Q
. . . . . Q . .
. . Q . . . . .
. . . . . . Q .
. Q . . . . . .
. . . Q . . . .
```

## File Structure

- `NQUEENS.c`: Main C source file containing the solver implementation.
- `README.md`: This file.

## Notes
- The program prints all solutions to the console. For large N, the output can be extensive.
- The code is written in standard C and should compile on any system with a C compiler.

## Author
David Chousal