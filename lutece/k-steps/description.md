
# Content

Here are $n$ beautiful towns and m roads(directional edge). yjx wants to visit these towns for relaxation when he suddenly 
got a question. He wants to know the number of schemes to walk from town $A$ to town $B$ in exactly $k$ steps.A road can be 
visited more then once. It takes exactly one step to walk from one town to another if they are directly connected by a road.

yjx is very entangled with this matter, please help him.

# Standard Input

First line is a number $T$, the number of the cases.

Each case is as follows:

First line includes four number: $n, m, k, l$ which means $n$($1 \leq n \leq 100$)towns, $m$($1 \leq m \leq 1000$)roads, $k$($1\leq k\leq 1000$)steps,
and $l$ ($1\leq l\leq 1000$) lines test data.

Then there are $m$ lines, and each line is made up of two number $u, v$ ($u \neq v$, $1\leq u,v \leq n$) which means one road from $u$ to $v$.

Then l lines test data, and each line is made up of two number $p, q$ (so you must help yjx to know the number of the scheme that
just walk $k$ steps from town $p$ to town $q$).

hint: maybe there are more than one road from $u$ to $v$ .

# Standard Output

For each test data, output the number of the scheme(the number is big, so you must make the number mod $1991$).

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
2 2 1 2
1 2
2 1
1 2
2 1
3 2 2 1
1 2
2 3
1 3</td><td>1
1
1</td></tr></table>


# Constraints



# Note



# Source


