
# Content

现在有$n$个囚笼，需要关押$m$个犯人，the big brother很担心囚笼的安全性，因为犯人都有自己的想法，他们只想住在特定的囚笼里面，那么big brother想知道最多 能关押多少个犯人，每个囚笼只能关押一个犯人，一个犯人也只能关押在一个囚笼里面。

# Standard Input

第一行 两个整数，$N (0 \leq N \leq 200)$ 和 $M (0 \leq M \leq 200)$ 。$N$ 是犯人的数量，$M$ 是囚笼的数量。

第二行到第$N+1$行 一共 $N$ 行，每行对应一只犯人。第一个数字 $(Si)$ 是这哥犯人愿意待的囚笼的数量 $(0 \leq Si \leq M)$。后面的$Si$个数表示这些囚笼的编号。

囚笼的编号限定在区间 $(1..M)$ 中，在同一行，一个囚笼不会被列出两次。

# Standard Output

只有一行。输出一个整数，表示最多能分配到的囚笼的数量.

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
<tr><td>5 5
1 1
1 2
1 3
1 4
1 5</td><td>5</td></tr></table>


# Constraints



# Note



# Source


