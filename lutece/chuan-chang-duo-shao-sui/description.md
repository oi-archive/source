
# Content

Krolia提示：在这题中，最好避免使用double型数据来进行条件判断，否则可能会出现可怕的精度误差导致不能通过该题。

船上有$78$只牛，$32$只羊。请问船长几岁？
觉得这道题莫名其妙？
先别下结论，让我们看一下成为船长的条件：
1. 有大专学历。就是说至少$21$岁。
2. 不同载重的船，对船长的资历有不同的要求。
  1. $500$吨及以下，对船长无资历要求。
  2. 超过$500$吨，不超过$1000$吨，船长至少从业$6$年。
  3. $1000$吨以上，船长至少从业$8$年。
3. **在该船长所在国家，对羊十分喜爱，对牛却十分厌恶，所以船长的船上要么只有牛，要么牛的数量减去羊的数量不大于自己的年龄。**

所以，我们可以推测出船长至少有多大岁数。

现在船上有$a$只牛，$b$只羊,告知你一头牛的重量$c$(千克)和一只羊的重量$d$(千克),请问船长至少几岁？

约定：
* 输入数据保证有解。
* $0\leq a,b,c,d\leq 10000$

# Standard Input

多组测试数据。

第一行是一个整数$T$，表示数据组数。（$T\leq 100$）

每组数据只包含$4$个整数$a$ $b$ $c$ $d$，分别代表船上牛的数量，船上羊的数量,一头牛的重量，一只羊的重量。

# Standard Output

对每组数据输出一个数$n$，表示船长至少的年龄。

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
78 32 500 250</td><td>46</td></tr></table>


# Constraints



# Note



# Source


