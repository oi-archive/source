
# Content

Giving a collection S of points on two dimension plane. ($S =$ {$(x\_0,y\_0), (x\_1,y\_1), \cdots $}) We define a point is greater than another point when all its coordinate on two axis are both greater than or equel to another one. Namely, $p$ is greater than $q$ when $x\_p \geq x\_q$ and $y\_p \geq y\_q$. A sequence is a list points < $p\_1, p\_2, \cdots $> satisfy that $i < j => p\_i$ is greater than $p\_j$. You can use the elements in $S$ to construct sequences, how many sequences needed to cover a $S$ at least?

# Standard Input

The input consists of several test cases. Each test case start with a line containing a number $n(0 < n \leq 1000000)$, the number of points in $S$. Then $n$ lines follows, each line containing two number, $x\_i, y\_i(0 \leq x\_i, y\_i < 100000)$, the position of point $i$. The input end with EOF.

# Standard Output

You have to print minium number of sequences needed to cover $S$ in a single line for each case.

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
<tr><td>4
1 1
2 2
3 3
4 4

4
1 5
2 6
2 3
3 4</td><td>1
2</td></tr></table>


# Constraints



# Note



# Source


