
# Content

Bob是一个魔法师。这天，他被$N$座山所阻挡，这些山排成一排，每座山有一个高度。Bob需要从左往右每次跳到相邻的一座山上，相邻的两座山的高度差不能超过$K$，当从高度差为$D$的一座山跳到另一座山时要花$A\times D$的魔法值。Bob可以改变一座山的高度，但调整后的高度不能小于$0$或大于$1000$，改变$S$的高度需要花费$S\times S$的魔法值。现在已知每座山的高度，求Bob跳完所有山后魔法值的最少花费。

# Standard Input

第一行一个整数$T$($T\leq 150$)，表示数据组数。

每组第一行有$3$个整数$N$($1\leq N\leq 1000$), $K$($0\leq K\leq 1000$), $A$($0\leq A\leq 1000$)。

接下来$N$个整数，按从左往右的顺序表示山的高度,山的高度在$0$到$1000$之间。

# Standard Output

对于每组数据，输出一个整数，表示最少花费。

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
1 1 1
1
3 1 10
1 2 3</td><td>0
2</td></tr></table>


# Constraints



# Note



# Source


