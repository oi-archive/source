
# Content

给定一颗n个结点的树，初始1号点为红色，其余点为蓝色。需要你设计数据结构实现两种功能。

1.将某个点涂为红色（若已为红色则无需更改）。

2.对于一个给出的点，输出从（此点）到（距离此点最近的红色点）的距离。

# Standard Input

第一行两个数n，m。代表树有n个结点，操作有m个。

接下来n - 1行，每行两个数u,v。代表这个树的边，其中u是根。

接下来m行，每行两个数，op，x

若op == 1，则将x涂红。

若op == 2，则输出从x到（距离x最近的红色点）的距离。

# Standard Output

对于每个op == 2，一行一个数表示答案。

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
<tr><td>5 4
1 2
2 3
2 4
4 5
2 1
2 5
1 2
2 5</td><td>0
3
2
</td></tr></table>


# Constraints

N = M = 100000

op = 1 or 2

1 <= x <= N

# Note

It seems that our oj paodebisheidoukuai.If you passed this prob by brute force,but your solution which will be sent to us is not efficient enough,you wouldn't get this score.

# Source


