
# Content

$N$ soldiers from the famous "**`FFF`** army'' is standing in a line, from left to right.

```
 o   o   o   o   o   o   o   o   o   o   o   o   o   o   o   o   o   o
/F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\ /F\
/ \ / \ / \ / \ / \ / \ / \ / \ / \ / \ / \ / \ / \ / \ / \ / \ / \ / \
```

You, as the captain of **`FFF`**, want to divide them into smaller groups, but each group should still be continous in the original line. Like this:
```
 o   o   o  |  o   o   o   o  |  o   o   o   o   o   o  |  o   o   o   o   o 
/F\ /F\ /F\ | /F\ /F\ /F\ /F\ | /F\ /F\ /F\ /F\ /F\ /F\ | /F\ /F\ /F\ /F\ /F\
/ \ / \ / \ | / \ / \ / \ / \ | / \ / \ / \ / \ / \ / \ | / \ / \ / \ / \ / \
```

In your opinion, the number of soldiers in each group should be no more than $L$.

Meanwhile, you want your division be `holy`. Since the soldier may have different heights, you decide that for each group except the first one, its last soldier(which is the rightmost one) should be strictly taller than the previous group's last soldier. That is, if we set $b\_i$ as the height of the last soldier in group $i$. Then for $i\geq 2$, there should be $b\_i >b\_{i-1}$.

You give your division a score, which is calculated as $\sum{(b\_k^2-b\_{k-1})}$, $b\_0=0$ and $1\leq k\leq M$, if there are $M$ groups in total. Note that $M$ can equal to $1$.

Given the heights of all soldiers, please tell us the best score you can get, or declare the division as impossible.

# Standard Input

The first line has a number $T$ ($T\leq 10$) , indicating the number of test cases.

For each test case, first line has two numbers $N$ and $L$ ($1 \leq L \leq N \leq 10^5$), as described above.

Then comes a single line with $N$ numbers, from $H\_1$ to $H\_n$, they are the height of each soldier in the line, from left to right. ($1 \leq H\_i \leq 10^5$)

# Standard Output

For test case $X$, output `Case #X: ` first, then output the best score.

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
5 2
1 4 3 2 5
5 2
5 4 3 2 1</td><td>Case #1: 31
Case #2: No solution</td></tr></table>


# Constraints



# Note



# Source


