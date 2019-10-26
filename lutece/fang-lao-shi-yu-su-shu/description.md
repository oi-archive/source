
# Content

方老师最近很喜欢素数，他想玩一个游戏：

现在有两个$4$位的素数$n$和$m$，你一次可以改变$n$的一位数字，并且改变过后的新数字必须也是个素数，并且也不能有前导$0$。请问使$n$变为$m$最少需要多少步。

例如$n=1033$ $m=8179$

那么可行的变化是：
```
1033
1733
3733
3739
3779
8779
8179
```

# Standard Input

第一行有一个整数$T(T \leq 100)$，代表测试数据的组数。

对于每组数据，每行有两个$4$位素数$N，M$（没有前导$0$）

# Standard Output

对于每一组数据,如果能够得到$m$，输出最少的步数，否则输出`Impossible`

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
<tr><td>3
1033 8179
1373 8017
1033 1033</td><td>6
7
0</td></tr></table>


# Constraints



# Note



# Source


