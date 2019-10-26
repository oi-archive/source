
# Content

Farmer John has noticed that his cows often move between nearby fields. Taking this into account, he wants to plant enough grass in each of his fields not only for the cows situated initially in that field, but also for cows visiting from nearby fields.

Specifically, FJ's farm consists of $N$ fields ($1 \leq N \leq 100,000$), where some pairs of fields are connected with bidirectional trails ($N-1$ of them in total). FJ has designed the farm so that between any two fields i and j, there is a unique path made up of trails connecting between $i$ and $j$. Field $i$ is home to $C(i)$ cows, although cows sometimes move to a different field by crossing up to $K$ trails ($1 \leq K \leq 20$).

FJ wants to plant enough grass in each field i to feed the maximum number of cows, $M(i)$, that could possibly end up in that field -- that is, the number of cows that can potentially reach field $i$ by following at most $K$ trails. Given the structure of FJ's farm and the value of $C(i)$ for each field $i$, please help FJ compute $M(i)$ for every field $i$.

# Standard Input

* Line $1$: Two space-separated integers, $N$ and $K$.
* Lines $2\cdots N$: Each line contains two space-separated integers, $i$ and $j$
($1 \leq i,j \leq N$) indicating that fields $i$ and $j$ are directly
connected by a trail.
* Lines $N+1\cdots 2N$: Line $N+i$ contains the integer $C(i)$. ($0 \leq C(i) \leq
1000$)

# Standard Output

* Lines $1\cdots N$: Line $i$ should contain the value of $M(i)$.

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
<tr><td>6 2
5 1
3 6
2 4
2 1
3 2
1
2
3
4
5
6</td><td>15
21
16
10
8
11</td></tr></table>


# Constraints



# Note



# Source


