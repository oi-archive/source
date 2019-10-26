
# Content

$N$ children are living in a tree with exactly $N$ nodes, on each node there lies either 
a boy or a girl. 

A girl is said to be protected, if the distance between the girl and her nearest boy is no more than $D$.

You want to do something good, so that each girl on the tree will be protected. On each 
step, you can choose two nodes, and swap the children living on them. 

What is the minimum number of steps you have to take to fulfill your wish?

# Standard Input

The first line has a number $T$ ($T\leq 150$) , indicating the number of test cases.

In a case, the first line contain two number $n$ ($1\leq n\leq 50$), $D$ ($1\leq D\leq 10000000$), Which 
means the number of the node and the distance between the girls and boys.

The next lines contains $n$ number. The $i\_{th}$ number means the $i\_{th}$ node contains a girl 
or a boy. ($0$ means girl $1$ means boy), The follow $n-1$ lines 
contains $a$, $b$, $w$, means a edge connect $a\_{th}$ node and $b\_{th}$ node, and 
the length of the edge is $w$ ($1\leq w\leq 10000000$).

# Standard Output

For every case, you should output `Case #t: ` at first, without quotes. 
The $t$ is the case number starting from $1$.

Then follows the answer, $-1$ meas you can't comlete it, 
and others means the minimum number of the times.

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
3 1
0 0 1
1 2 1
1 3 1</td><td>Case #1: 1</td></tr></table>


# Constraints



# Note



# Source


