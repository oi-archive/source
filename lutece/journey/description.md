
# Content

Bob has traveled to byteland, he find the $N$ cities in byteland formed a tree structure, a tree structure
is very special structure, there is exactly one path connecting each pair of nodes, and a tree with $N$
nodes has $N-1$ edges.

As a traveler, Bob wants to journey between those $N$ cities, and he know the time each road will cost.
he advises the king of byteland building a new road to save time, and then, a new road was built. Now Bob
has $Q$ journey plan, give you the start city and destination city, please tell Bob how many time is saved
by add a road if he always choose the shortest path. Note that if it's better not journey from the new roads,
the answer is $0$.

# Standard Input

First line of the input is a single integer $T$($1\leq T \leq 20$), indicating there are $T$ test cases.

For each test case, the first will line contain two integers $N$($2 \leq N \leq 10^5$) and $Q$($1 \leq Q \leq 10^5$), indicating
the number of cities in byteland and the journey plans. Then $N$ line followed, each line will contain three
integer $x$, $y$($1 \leq x,y \leq N$) and $z$($1 \leq z \leq 1000$) indicating there is a road cost $z$ time connect
the $x^{th}$ city and the $y^{th}$ city, the first $N-1$ roads will form a tree structure, indicating the original roads,
and the $N^{th}$ line is the road built after Bob advised the king. Then $Q$ line followed, each line will contain two
integer $x$ and $y$($1 \leq x,y \leq N$), indicating there is a journey plan from the $x^{th}$ city to $y^{th}$ city.


# Standard Output

For each case, you should first output `Case #t:` in a single line, where $t$ indicating the case number between $1$ and $T$,
then $Q$ lines followed, the $i^{th}$ line contains one integer indicating the time could saved in $i^{th}$ journey plan.


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
5 5
1 2 3
2 3 4
4 1 5
3 5 1
3 1 5
1 2
1 3
2 5
3 4
4 5
</td><td>Case #1:
0
2
0
2
2
</td></tr></table>


# Constraints



# Note



# Source


