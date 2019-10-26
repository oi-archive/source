
# Content

You have a rectangular piece of paper that is divided into $1 \times 1$ cells, each of which has an integer value.

You want to perform a sequence of folds on the paper, where you may fold anywhere along an axis that is in between
two rows or columns of the paper. After performing all the folds you want, the overlapping cells will be considered
as a single cell, whose value is the sum of the individual cells.

You want the biggest number in the resulting piece of paper to be as large as possible, what is the biggest number
you can get ?

# Standard Input

First line of the input is a single integer $T$($1\leq T \leq 10$), indicating there are $T$ test cases. For each test case,
the first line contains two integers, $N$ and $M$ ($1\leq N\leq 20,1\leq M\leq 500$), indicating the length and width of the
paper. Then $N$ lines followed, each line contains $M$ integers $x_i$($-10^4 \leq x_i \leq 10^4$), indicating the numbers in
the original piece of paper.

# Standard Output

For each case,output `Case #t: ret` in a single line, where $t$ indicating the case number between $1$ and $T$, and
$ret$ is the biggest number you can get in the resulting piece of paper.

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
<tr><td>2
2 2
1 -2
3 -4
2 5
1 -2 -3 4 -5
6 -7 -8 9 -10</td><td>Case #1: 4
Case #2: 20</td></tr></table>


# Constraints



# Note

1. Of course, if you do not fold any cells, the value of each cell is its original value.
2. Explanation for the 2nd Case in Sample Input

  ![.*](/source/lutece/fold-the-paper/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODgvMjAxNDAxMTMxODAyNDA5MzgyLmpwZw==.jpg)
3. Note that merging the overlapping cells only happens after all the folds, which means:

  ![.*](/source/lutece/fold-the-paper/img/aHR0cHM6Ly9hY20udWVzdGMuZWR1LmNuL21lZGlhL2ltYWdlL3Byb2JsZW0vODgvMjAxNDAxMTMxODAyNDgwMjMzLmpwZw==.jpg)

# Source


