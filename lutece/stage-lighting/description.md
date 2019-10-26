
# Content

在一个舞台上从左到右摆放着$n$盏灯，灯的编号是$1$到$n$，第$i$盏灯的功率是$p_i$。

当点亮的灯的总功率之和不小于$Z$时，演出就开始啦！

点亮一盏灯，需要连上一定数量的电源。第$i$盏灯如果要点亮，需要将它和$k\_i$个电源相连，电源的编号分别是$a\_{i,1}$, $a\_{i,2}$, $\dots$, $a\_{i, k\_i}$。

现在舞台一共有$K$个电源，编号从$1$到$K$，每个电源同时最多只能和一盏灯相连。

给定以上信息，你需要对每个$i$，求出最小的$r_i\geq i$，使得可以从$[i, r_i]$中选一些灯点亮，使演出开始，如果这样的$r_i$不存在，输出$-1$。

# Standard Input

第一行输入$n$, $K$和$Z$。（$1\leq n\leq 10^5$, $1\leq K\leq 8$, $1\leq Z\leq 10^9$）

第二行包括$n$个整数$p\_1$, $p\_2$, $\dots$, $p\_n$，表示每盏灯的功率。（$1\leq p\_i\leq 10^9$）

接下来$n$行，第$i$行的第一个数字为$k\_i$，表示点亮第$i$盏灯需要的电源个数（$1\leq k\_i \leq K$）。之后的$k\_i$个数，$a\_{i,1}$, $a\_{i,2}$, $\dots$, $a\_{i, k\_i}$，表示对应电源的编号。（$1\leq a\_{i, j}\leq K$）

# Standard Output

输出$n$行，每行是对应的$r_i$。

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
<tr><td>6 3 6
3 1 3 5 6 4
1 2
1 3
1 1
1 2
3 1 2 3
2 1 3
</td><td>3
4
4
5
5
-1
</td></tr></table>


# Constraints



# Note



# Source


