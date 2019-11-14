
# Content

Examine the $6\times 6$ checkerboard below and note that the six checkers are arranged on the board so that one and only one is placed in each row and each column, and there is never more than one in any diagonal. (Diagonals run from southeast to northwest and southwest to northeast and include all diagonals, not just the major two.)

```
    1   2   3   4   5   6
  -------------------------
1 |   | O |   |   |   |   |
  -------------------------
2 |   |   |   | O |   |   |
  -------------------------
3 |   |   |   |   |   | O |
  -------------------------
4 | O |   |   |   |   |   |
  -------------------------
5 |   |   | O |   |   |   |
  -------------------------
6 |   |   |   |   | O |   |
  -------------------------
```

The solution shown above is described by the sequence `2 4 6 1 3 5`, which gives the column positions of the checkers for each row from $1$ to $6$:

```
ROW    1	2	3	4	5	6
COLUMN 2	4	6	1	3	5
```

This is one solution to the checker challenge. Write a program that finds all unique solution sequences to the Checker Challenge (with ever growing values of $N$). Print the solutions using the column notation described above. Print the the first three solutions in numerical order, as if the checker positions form the digits of a large number, and then a line with the total number of solutions.

# Standard Input

A single line that contains a single integer $N$ ($6\leq N\leq 13$) that is the dimension of the $N\times N$ checkerboard.

# Standard Output

The first three lines show the first three solutions found, presented as $N$ numbers with a single space between them. The fourth line shows the total number of solutions found.

# Samples

<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>Input</td>
		<td>Output</td>
	</tr>
<tr><td>6</td><td>2 4 6 1 3 5
3 6 2 5 1 4
4 1 5 2 6 3
4</td></tr></table>


# Constraints



# Note



# Source


