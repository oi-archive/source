
# Content

在一根细木杆上，有一些速度相同蚂蚁，它们有的往左走，有的往右走，木杆很细，只允许一只蚂蚁通过，所以当两只蚂蚁碰头的时候，它们会掉头继续前进，直到走出边界，掉下木杆。

已知木杆的长度和每只蚂蚁的名字、位置和初始方向，问依次掉下木杆的蚂蚁花费的时间以及它的名字。

# Standard Input

输入包含多组测试数据。

第一行包含一个整数$T$($T\leq 20$)，代表测试数据组数。

每组测试数据的第一行包含两个整数$N$, $L$，表示有$N$只蚂蚁($N\leq 100$)，木杆长度为$L$($L\leq 1000$)。假设蚂蚁每秒前进一个单位距离，掉头转向的时间忽略不计。

以下$N$行，每行依次为蚂蚁的名字（长度不超过$10$，仅由英文字母组成），初始位置$p$（$0 < p < L$，整数，表示蚂蚁离木杆最左端的距离），初始方向（一个字符，`L`表示向左，`R`表示向右），以单个空格分隔，数据保证初始不会有两只蚂蚁在同一个位置。

# Standard Output

对于第$k$组测试数据，首先输出一行为`Case #k:`。

然后输出$N$行，给出依次掉下木杆的蚂蚁花费的时间以及它的名字，以单个空格分隔。
（按照掉下木杆的先后顺序输出，数据保证不会有两支蚂蚁同时掉下木杆）。

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
2 5
GG 1 L
MM 3 R
2 5
GG 1 R
MM 2 L</td><td>Case #1:
1 GG
2 MM
Case #2:
2 GG
4 MM</td></tr></table>


# Constraints



# Note



# Source


