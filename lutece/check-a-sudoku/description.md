
# Content

Sudoku is a puzzle of a $9 \times 9$ grid made up of $3 \times 3$ subgrids (called `regions`).Some cells already contain numbers, known as `givens`. The goal is to fill in the empty cells, one number in each, so that each column, row, and region contains the numbers $1$ through $9$ exactly once. Each number in the solution therefore occurs only once in each of three "`directions`, hence the `single numbers` implied by the puzzle's title.

![title](/source/lutece/check-a-sudoku/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vMjY3LzIwMTQwMzE4MjIyMDQxNDc5MjUucG5n.png)

The attraction of the puzzle is that the completion rules are simple, yet the line of reasoning required to reach the completion may be difficult. Published puzzles often are ranked in terms of difficulty. This also may be expressed by giving an estimated solution time. While, generally speaking, the greater the number of givens, the easier the solution, the opposite is not necessarily true. The true difficulty of the puzzle depends upon how easy it is to logically determine subsequent numbers.

TheBeet is fond of this game, he has solve lots of sudokus. But one day, when he check the puzzles he had solve before, some of them does not look correct.
Now TheBeet is busy with his homework. As one of the best programmer in XMU, could you kind enough to help TheBeet to check the puzzles?

# Standard Input

The first line of the input contains one integer $n (n < 20)$, which represents the number of test cases.

Each test case contains $9$ lines, each line contains $9$ integers, which represent the answer to the puzzle you should check.

There is a blank line after each test case.

# Standard Output

For each test case, output `Case #:` on the first line, `#` is the number of the test case; then you should output`Yes!` (without quotes) if the answer is correct, otherwise you should output `No!`.

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
<tr><td>1
5 6 2 8 3 9 1 4 7
7 1 4 5 2 6 8 3 9
3 8 9 1 4 7 2 6 5
1 2 8 9 5 3 6 7 4
6 4 5 7 1 8 9 2 3
9 3 7 4 6 2 5 1 8
2 9 6 3 8 4 7 5 1
4 7 1 2 9 5 3 8 6
8 5 3 6 7 1 4 9 2</td><td>Case 1:
Yes!</td></tr></table>


# Constraints



# Note



# Source


