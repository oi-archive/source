
# Content

机房里面有$m$台电脑，$n$台网线，每条网线都每秒中最多传送的数据量，现在需要你计算从标号为1的电脑传送数据到编号为$m$的电脑，问一秒内最多传送多少数据?

# Standard Input

第1行: 两个用空格分开的整数$N (0 \leq N \leq 200) $和 $M (2 \leq M \leq 200)$。$N$网线的数量，$M$是电脑的数量。

第二行到第$N+1$行: 每行有三个整数，$Si$，$Ei$ 和 $Ci$。$Si$ 和 $Ei$ $(1 \leq Si, Ei \leq M)$ 指明电脑编号，数据从 $Si$ 流向 $Ei$。$Ci (0 \leq Ci \leq 10,000,000)$是这条网线的最大容量。

# Standard Output

输出一个整数，即排水的最大流量。

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
1 2 40
1 4 20
2 4 20
2 3 30
3 4 10</td><td>50
</td></tr></table>


# Constraints



# Note



# Source


