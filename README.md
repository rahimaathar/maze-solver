# Maze Solver

A simple web application that solves mazes using a recursive backtracking algorithm.

## How it works

The maze solver reads maze data and finds a path from the start point to the finish point. It uses a recursive approach to explore all possible paths until it finds a solution.

## Input Format

The maze data should be provided in the following format:

```
Rows: 6
Cols: 6
Start: (1,5)
Finish: (4,0)
(0,1)
(0,2)
(1,2)
(1,4)
(1,5)
(2,2)
(2,4)
(3,0)
(3,1)
(3,2)
(3,3)
(3,4)
(4,0)
(4,2)
(5,1)
(5,2)
(5,3)
(5,4)
```

- First line: Number of rows
- Second line: Number of columns  
- Third line: Start coordinates (row, col)
- Fourth line: Finish coordinates (row, col)
- Remaining lines: Valid path coordinates

## Legend

- **X**: Wall (blocked path)
- **S**: Start position
- **F**: Finish position
- **P**: Path from start to finish

## Usage

1. Open the HTML file in your browser
2. Enter maze data in the text area
3. Click "Solve Maze" button
4. View the solution path

## Files

- `index.html` - Main web application
- `26100301_PA03_TASK1.cpp` - Original C++ implementation
- `maze.txt` - Sample maze data

## Deployment

This project can be deployed on Vercel by simply uploading the files. The HTML file contains all necessary code to run the maze solver in a web browser.
