
# Content

To get big integers, we can concatenate small integers together, such as concatenate $32$ and $1$ to $321$, or concatenate $3$ and $21$ to $321$.

There is a set $S$ containing $N$ different integers. An integer $X$ is special if the following three conditions are satisfied:

1. Choose two nonempty subsets $A$ and $B$ from $S$, where $A$ and $B$ have no common elements.

1. There is at least one way to get $X$ by concatenating all numbers in $A$.

1. There is at least one way to get $X$ by concatenating all numbers in $B$.

Output the largest special integer $X$.

# Standard Input

A single integer $T$ in the first line, indicating the number of cases.

For each case:

There are multiple test cases.

A single integer $N$ is given in the first line.

$N$ different integers $a_1$, $a_2$, ..., $a_N$ are given in the second line.

$1\leq T \leq 50$

$2 \leq N \leq 6$;

$0 \leq a_i \leq 99$, $1 \leq i \leq N$;

There are no leading zeros.

`CF`：参加`div.1`的同学的最终得分 = 所有参加`div.2`同学$A$题的最高的$10$个得分的平均分 + 所有参加`div.2`同学$B$题的最高的$10$个得分的平均分 + 该同学`div.1`$A$题得分 $\times \frac{div.2 C题满分}{div.1 A题满分}$ + 该同学`div.1`$B$题得分 $\times \frac{div.2 D题满分}{div.1 B题满分}$ + 该同学`div.1`$C$题得分 $\times \frac{div.2 E题满分}{div.1 C题满分}$ + 该同学`div.1`$D$题得分$\times 3$ + 该同学`div.1`$E$题得分 $\times$ $5$ 

`TC`：参加`div.1`的同学的最终得分 =所有参加`div.2`同学$A$题的最高的$10$个得分的平均分 + 该同学`div.1`$A$题得分 $\times \frac{div.2 B题满分}{div.1 A题满分}$ +该同学`div.1`$B$题得分 $\times \frac{div.2 C题满分}{div.1 B题满分}$ + 该同学`div.1`$C$题得分 $\times$ $5$

# Standard Output

For each case, output "Case #i " first, $i$ is the case number, from $1$ to $T$. Then if you can get at least one special integer, output the largest one. Otherwise, output `-1`.

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
<tr><td>3
4
1 3 32 21
4
1 2 12 21
2
1 2</td><td>Case #1: 321
Case #2: 21
Case #3: -1</td></tr></table>


# Constraints



# Note



# Source


