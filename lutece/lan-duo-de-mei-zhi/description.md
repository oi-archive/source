
# Content

cjw是个很懒的人，每次只要上二楼都要坐电梯，而且cjw做事很随意，一般是玩dota玩到一半突然想起快上课了(她说谁想找虐的有空找她玩)，就赶紧跑去上课了。现在cjw会在$[a,b]$($0\leq a<b$)的任一时刻到达第一层楼，但是cjw最多只能等待$t$时间，如果等待$t$时间后电梯还没有开始上升，她就会哭着走上楼T____T。

今天电梯抽风了，电梯只向上走一次，刚开始在第一层楼，且开始运动的时间是$t\_1$，到达最后一层后电梯就不再工作。

现在cjw想知道自己乘上电梯的概率是多大。她数学太差了，算不出来，你能帮她算出来吗?

题目中提到的时间量单位均为秒。

**cjw在$[a,b]$每个时刻到达的概率相等。**

# Standard Input

第一行一个整数T表示有$T$组测试数据（$T\leq 5000$）

每组数据输入四个整数 $a,b,t,t\_1$($0\leq a<b\leq 1000000$, $0\leq t\leq 500000$, $0\leq t\_1\leq 1000000$)。

# Standard Output

每组数据输出一行，仅含一个实数表示cjw乘上电梯的概率（**保留$4$位小数**）。

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
5 10 5 10
2 5 2 6</td><td>1.0000
0.3333</td></tr></table>


# Constraints



# Note

输入量很大，请使用`scanf`代替`cin`来输入。

为了避免可能出现的精度问题，请使用`double`代替`float`，使用`%lf`读入，`%f`输出。

# Source


