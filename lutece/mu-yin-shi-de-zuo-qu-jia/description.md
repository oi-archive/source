
# Content

Shintaro是一个废宅同时也喜欢做一些原创音乐。但是最近他的电脑被一个叫做`ENE`的病毒感染了，ENE总是把Shintaro的乐谱全部转换成二进制的形式，而这样会使Shintaro的乐谱产生歧义导致自己也看不懂自己的乐谱，这让Shintaro烦恼不已。

Shintaro的乐谱里面只有`do`, `re`, `mi`, `fa`, `so`, `la`, `xi` 这$7$个音符，每个音符分别对应$1,2,3,4,5,6,7$这$7$个$10$进制数字，而ENE则会把这$7$个音符转换成这$7$个$10$进制数对应的二进制数，即是：$1,10,11,100,101,110,111$。例如：Shintaro的原乐谱若为`do`, `mi`，ENE则将其变成$111$，Shintaro 无法得知他之前的乐谱里面写的是`do`, `mi`还是`xi`。于是，Shintaro做了一个伟大的决定，他以后写乐谱时保证即使被改变成二进制也不会引起歧义，但是这样会严重限制到他创作范围，Shintaro想知道如果要做一首长度（即指乐谱中音符的个数）为$n$的乐曲可以写出多少种满足条件的不同乐谱，于是找你来帮忙写个程序来解决这个问题。

注意：在本题中，乐谱中不能有休止符`0`。

# Standard Input

第一行为一个整数$T$，代表数据组数($T\leq 20$)

之后每行一个整数$n$ ($0 < n\leq 100$)

# Standard Output

每组数据输出一行，输出一个整数，表示能够创作出的符合条件的不同的乐谱数量。由于输出数据可能很大，只用输出乐谱数量$mod\ 10^9+9$ 的余数即可。

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
2</td><td>6</td></tr></table>


# Constraints



# Note



# Source


