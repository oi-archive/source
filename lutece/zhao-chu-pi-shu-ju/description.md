
# Content

在科学研究中，经常要对实验数据进行处理。小S已经测量出了$n$个实验数据，其中可能有一些数据是坏数据，即不合乎逻辑的数据，这可能是他前一天晚上玩游戏太晚的缘故。请你帮他找出其中的坏数据，并对剩下数据作如下操作：
1. 求出它们的平均值$A$
2. 求出每个数与平均值差的平方，并求和，然后开方再除以合理数据的个数，记该结果为$S$

为了方便找出坏数据，小S给出了合理数据的区间$[a,b]$。

# Standard Input

有多组测试数据。输入的第一行是整数$T$（$0<T\le 100$），表示测试数据的组数。每一组测试数据只有一行，前三个数据是$n$、$a$和$b$，分别表示这组数据的个数和合理数据区间$[a,b]$。接下来是$n$个实验数据。该行每个数据后均有一个空格。该行没有其它多余的符号。其中$10\le n\le 1000$，实验数据均为非负数，不超过$10^6$。这里的数据都是整数。

# Standard Output

对应每组输入，输出一行结果，分别为平均值$A$和$S$，保留两位小数。两数之间用一个空格隔开，行尾没有空格。该行不能有其它多余的符号。

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
<tr><td>1
4 2 3 1 2 3 4</td><td>2.50 0.35</td></tr></table>


# Constraints



# Note



# Source


