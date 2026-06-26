# Matrix Data Analyzer

A beginner-friendly Python project that builds a 3×3 matrix from user input and performs several analyses on the stored values.

## Features

- Creates a 3×3 matrix
- Displays the matrix in a formatted layout
- Calculates the sum of all even numbers
- Calculates the sum of the third column
- Finds the largest value in the second column
- Demonstrates nested loops and matrix traversal

## Technologies Used

- Python 3

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/matrix-data-analyzer.git
```

2. Navigate to the project folder:

```bash
cd matrix-data-analyzer
```

3. Run the script:

```bash
python main.py
```

## Example

### Input

```text
Enter the value for position [0][0]: 5
Enter the value for position [0][1]: 8
Enter the value for position [0][2]: 1
Enter the value for position [1][0]: 6
Enter the value for position [1][1]: 9
Enter the value for position [1][2]: 3
Enter the value for position [2][0]: 4
Enter the value for position [2][1]: 2
Enter the value for position [2][2]: 7
```

### Output

```text
[  5 ][  8 ][  1 ]
[  6 ][  9 ][  3 ]
[  4 ][  2 ][  7 ]

The sum of the even values is 20
The sum of the third column is 11
The largest value in the second column is 9
```

## Learning Objectives

This project demonstrates:

- Two-dimensional lists (matrices)
- Nested `for` loops
- Matrix traversal
- Conditional statements
- Accumulators
- Finding the maximum value
- Formatted output

## Key Concepts

### Matrix Initialization

```python
matrix = [[0, 0, 0], [0, 0, 0], [0, 0, 0]]
```

Creates a 3×3 matrix filled with zeros.

### Nested Loops

```python
for row in range(3):
    for column in range(3):
```

Allow the program to visit every position in the matrix.

### Even Number Check

```python
value % 2 == 0
```

Determines whether a number is even.

### Column Access

The third column has index `2`:

```python
matrix[row][2]
```

The second column has index `1`:

```python
matrix[row][1]
```
