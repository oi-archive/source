
# Content

Farmer John's $N$ ($1\leq N\leq 10,000$) cows (conveniently numbered $1\cdots N$) graze in a straight line in their pasture whose length is $L+1$ ($N\leq L\leq 100,000$) meters. Every morning, they place themselves at various unique integer locations along that line. FJ has observed that the cows produce more milk when the distance to the other grazing cows is maximized. Always the enterprising farmer, FJ wants to maximize the distance between each and every pair of neighboring cows by moving the cows to the right or left, but always with integer inter-cow spacing and never changing their order on the line. He spends $1$ minute to move a cow $1$ meter. When he's finished, he knows that the distances between every adjacent pair of cows will be one of two integers: $D$ or $D+1$. Help FJ to calculate minimum time he needs to arrange the positions of the cows.

# Standard Input

Line $1$: Two space-separated integers, $N$ and $L$ 

Lines $2\cdots N+1$: Line $i+1$ describes cow $i$ with a single integer (range $0\cdots L$) representing the position of a cow; $0$ is the left-most position. The list is sorted by position with the smallest position value first.

# Standard Output

Line $1$: A single line with minimum time FJ needs to arrange the positions of the cows.

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
<tr><td>5 10
0
1
4
9
10</td><td>3</td></tr></table>


# Constraints



# Note

Explanation of the sample: 

The cows are arranged like this at the start: 
```
1 2 - - 3 - - - - 4 5
```
The cows end up arranged like this: 
```
1 - 2 - 3 - - 4 - - 5
```

Cow #$2$ moves from position $1$ to position $2$ ($1$ meter). Cow #$4$ moves from position $9$ to position $7$ ($2$ meters). Other cows don't move. Moving times are $1+2=3$, which is the final answer.

# Source


