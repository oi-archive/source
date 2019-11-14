
# Content

There are $N$ seaside villages on X island, numbered from $1$ to $N$. $N$ roads are built to connect all of them, which are also numbered from $1$ to $N$, and the road with number $i$ connects the village $i$ and $i$ % $N + 1$. Sometimes, for some reasons, some roads are blocked, so some villages are not connected anymore. Now, you are assigned to write a program to offer dynamic information about the connectivity.

At first, all roads are not blocked. The input will tell you the road with number $i$ are blocked or unblocked, or ask you if village $i$ and $j$ are connected. Here two villages are connected means we can reach another village from one via some unblocked road. BTW, all the roads are bidirectional.

# Standard Input

The first line of the input contains one integer $T$, which indicate the number of test cases. The very first line of each case contains two integers, $N$ and $M$. $N$ (where $2\leq N\leq 100000$) is the total number of the villages, $M$ (where $1\leq M\leq 100000$) is the number of queries. The next $M$ lines each describe one query. For each line, the first integer ($0$ or $1$) indicates the type of the query. If the first integer is $0$, there will be another integer $i$ followed, if the road $i$ is blocked at present, it will be unblocked, and vice versa. If the query type is $1$, there will be two more integers $i$ and $j$ followed, if the village $i$ and $j$ are connected at present, the answer is $1$, otherwise it shall be $0$.

# Standard Output

For each query of type $1$, output its answer in a single line

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
5 10
1 2 5
0 4
1 4 5
0 2
1 3 4
1 1 3
0 1
0 2
1 2 4
1 2 5</td><td>1
1
1
0
1
0</td></tr></table>


# Constraints



# Note



# Source


