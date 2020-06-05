
# Content

琴酒原本是黑衣组织的一员，但黑衣组织里卧底太多了，于是琴酒选择退出黑衣组织，当起了酒厂老板。

一共有 $n$ 个酒厂与 $m$ 条可选的运输路线，每条运输路线可以单向地将酒从一个酒厂运往另一个酒厂，并有一定的建造费用。为了方便管理，琴酒想将其中一个酒厂设置为总部，并选择若干条路进行建造，使得总部的酒可以运到其他酒厂。琴酒想知道最少的建造费用是多少。

# Standard Input

第一行两个整数 $n$ 和 $m$ ($2 \le n \le 1000, 1 \le m \le 10000$)，表示酒厂个数与运输路线的条数。

接下来 $m$ 行，每行三个整数 $u,v,w$ ($1 \le u,v \le n,u \neq v,1 \le w \le 10^5$)，表示一条从 $u$ 号酒厂运往 $v$ 号酒厂且建造费用为 $w$ 的运输路线。

# Standard Output

如果存在符合条件的建造方案，一行输出两个整数，第一个整数表示最少的建造费用，第二个整数表示对应的总部编号。如果有多个方案，输出最小的总部编号。

如果不存在符合条件的建造方案，输出 $-1$。

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
<tr><td>4 4
1 2 10
1 3 10
2 4 20
3 4 30</td><td>40 1</td></tr><tr><td>3 1
1 2 1</td><td>-1</td></tr></table>


# Constraints



# Note



# Source


