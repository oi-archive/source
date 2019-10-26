
# Content

OK，现在是new的NIM时间。距离上一次的NEW NIM已经过去了整整一年，这一年中new凭借new nim赢得了n多场胜利。不过天天玩一个实在是游戏太dt了，于是new又捣鼓除了一个新游戏--NEW^2 NIM(不许吐槽这也很dt)

新游戏是这样的：一共有$n+1$堆石子，第一堆石头有$2012$个，两个人分别进行操作。一次操作可以选取两堆不同的石堆分别增加或减少一个石子（一加一减，或给已经不剩石子的堆加一个都是允许的）。为了保证游戏会在有限步内结束，规定所选的两堆中右边的那一堆一定要包含奇数个石子,无路可走者输.
请问对于给出的状态先手是否必胜？

# Standard Input

第一行一个数T，表示$T$组数据

每组数据两行。第一行一个数$n$（$n\leq 100$），表示有$n+1$堆石头；第二行$n$个数，从左到右列出其它$n$堆石头的个数。

# Standard Output

`YES`表示先手必胜，`NO`表示后手必胜

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
2
2 3
6
2 4 3 6 5 7</td><td>YES
NO</td></tr></table>


# Constraints



# Note



# Source


