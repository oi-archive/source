
# Content

下凡的柱爷想只创造3种硬币，要求这3种硬币可以组成$[1,N]$的所有整数，并且表示一个$[1,N]$中的整数所用硬币的平均数量最少.

你能帮柱爷解决他的小小问题吗？

# Standard Input

第一行一个正整数$T$,表示测试组数.

接下来$T$行,每行一个正整数$N$.

数据保证:

* $1 \leq T \leq 200$

* $1 \leq N \leq 200$

# Standard Output

输出一共有$T$行,每行三个整数$A$ $B$ $C$表示柱爷希望的三种不同硬币的面值.如果有多组解,请保证A尽可能小,如果仍有多组解,请保证B尽量小,如果仍有多组解,请保证C尽量小.
$A < B < C$

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
1</td><td>1 2 3</td></tr><tr><td>1
7</td><td>1 2 5</td></tr></table>


# Constraints



# Note

当$N=7$时

* $1$元,需要$1$个$1$元
* $2$元,需要$1$个$2$元
* $3$元,需要$1$个$1$元和$1$个$2$元
* $4$元,需要$2$个$2$元
* $5$元,需要$1$个$5$元
* $6$元,需要$1$个$1$元和$1$个$5$元
* $7$元,需要$1$个$2$元和$1$个$5$元
* 平均需要约$1.57$个硬币.

# Source


