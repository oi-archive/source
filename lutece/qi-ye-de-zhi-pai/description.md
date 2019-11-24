
# Content

有$n$张卡片，每张卡片正面都有一个数字$v\_i，(1 \leq vi \leq m, 其中m \leq n)$。若某张卡片上的数字为$k$，则称该张卡片为第$k$种卡片。现在已知每种卡片的个数分别为$a\_i$。将这$n$张卡片随机的分为$m$堆，其中第i堆的卡片个数正好为$a\_i$。现在开始一个游戏，首先随机的从第一堆卡片中选出一张卡片扔掉，如果该卡片为第$k$种卡片，再随机的从第$k$堆卡片中选择一张卡片扔掉，一直这样重复下去。直到不能继续取出卡片游戏结束。求游戏结束时所有卡片都被扔掉的概率。

# Standard Input

第一行读入一个整数$T$，表示接下来有T组测试数据。

对于每一组数据，首先第一行读入一个$m$，表示共有$m$种不同的卡片。

接下来一行读入$m$个数$a\_i$，分别表示第$i$种卡片的个数。

$1 \leq T \leq 20, 1 \leq m \leq 100, 1 \leq a\_i \leq 1000$

# Standard Output

对于每一组数据，输出答案，保留$5$位小数。每组数据单独输出一行

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
1
5
2
1 2</td><td>1.00000
0.33333</td></tr></table>


# Constraints



# Note

C或C++的输出参考 printf("%.5f\n", ans); (ans为double类型)

# Source


