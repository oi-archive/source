
# Content

Ignatius再次被魔王抓走了(搞不懂他咋这么讨魔王喜欢)……

这次魔王汲取了上次的教训，把Ignatius关在一个$n\times m$的地牢里，并在地牢的某些地方安装了带锁的门，钥匙藏在地牢另外的某些地方。刚开始Ignatius被关在$(s\_x,s\_y)$的位置，离开地牢的门在$(e\_x,e\_y)$的位置。Ignatius每分钟只能从一个坐标走到相邻四个坐标中的其中一个。魔王每$t$分钟回地牢视察一次，若发现Ignatius不在原位置便把他拎回去。经过若干次的尝试，Ignatius已画出整个地牢的地图。现在请你帮他计算能否再次成功逃亡。只要在魔王下次视察之前走到出口就算离开地牢，如果魔王回来的时候刚好走到出口或还未到出口都算逃亡失败。

# Standard Input

每组测试数据的第一行有三个整数$n,m,t$($2\leq n,m\leq 20$, $t>0$)。接下来的$n$行$m$列为地牢的地图，其中包括:
* `.` 代表路
* `*` 代表墙
* `@` 代表Ignatius的起始位置
* `^` 代表地牢的出口
* `A`-`J` 代表带锁的门,对应的钥匙分别为`a`-`j`
* `a`-`j` 代表钥匙，对应的门分别为`A`-`J`

每组测试数据之间有一个空行。

# Standard Output

针对每组测试数据，首先输出$case$编号，接下来一个空格。

对于可以成功逃亡的情况，请输出需要多少分钟才能离开，如果不能则输出`-1`。

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
<tr><td>4 5 17
@A.B.
a*.*.
*..*^
c..b*

4 5 16
@A.B.
a*.*.
*..*^
c..b*</td><td>Case 1: 16
Case 2: -1</td></tr></table>


# Constraints



# Note



# Source


