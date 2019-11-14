
# Content

State machines occur frequently in computer science literature. At any given point in time, a state machine is in a particular state $p$. After receiving an input symbol, the machine updates its state. The potential input symbols in this problem are $0$, $1$, $2$, or $3$. Give you a transition list describes how the state machine $M$ behaves. Each element of the transition list will contain $4$ space delimited integers. The integers in element $i$ ($0$-based) describe how $M$ reacts to input while in state $i$. For example, if element $3$ is `0 4 2 3`, then $M$ will transition from state $3$ to state $0$, $4$, $2$, or $3$ depending on whether $0$, $1$, $2$, or $3$ are received as input, respectively. Our state machine $M$ is unfortunately out of control. We do not know which state $M$ is currently in. To rectify the situation, we want to find a string $s$ and a state $h$ such that, after feeding $s$ into $M$ one symbol at a time, $M$ will definitely be in state $h$. Considering all possible pairs of $s$ and $h$, output the length of the shortest $s$. If no such pairs exist, output $-1$.

# Standard Input

There are multi-cases. On the first line of each case, there is a integer $n$ ($n\leq 20$), the size of the transition list. Then $n$ lines followed, each line contains four integers $w$, $x$, $y$ and $z$ where $w$, $x$, $y$, and $z$ are integers, between $0$ and $n-1$ inclusive.

# Standard Output

For each case, output the length of the shortest $s$. If no such pairs exist, output $-1$.

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
1 1 1 1
1 1 1 2
0 2 2 2
4
1 1 1 1
2 2 2 2
3 3 3 3
0 0 0 0</td><td>2
-1</td></tr></table>


# Constraints



# Note



# Source


