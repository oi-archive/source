
# Content

方师傅有两个由数字组成的串 $a\_1, a\_2, \cdots , a\_n$ 和 $b\_1, b\_2, \cdots , b\_m$。 有一天，方师傅感到十分无聊因此他决定用这两个串来玩玩游戏。游戏规则十分简单，方师傅会进行一些操作，每个操作可能是以下两种操作之一：

 1.从$a$串选择一个$a$的非空前缀，再从$b$串选一个$b$的非空前缀。这两个前缀的最后一个元素必须相等，完成选择后把这两个前缀删除。

 2.删除两个串所有的元素。

第一种操作会耗费$e$的能量值，并为方师傅增加一美分到他的电子账户中。第二种操作会耗费两个串的不完整度的能量。不完整度 = 两个串已经被删除的元素的数目。只有执行第二种操作后，方师傅才能从电子帐户中取出他的钱。

刚开始时，方师傅有一个空的电子账户和s的能量，请问方师傅最多可以赚多少美分？注意，由于乐警官偷吃光了方师傅的士力架，导致方师傅无法补充能量，因此方师傅的能量任何时候都不能小于$0$。

# Standard Input

第一行$4$个整数，$n,m,s,e(1\leq n, m \leq 10^5; 1 \leq s \leq 3\times10^5; 10^3 \leq e \leq 10^4)$。

第二行$n$个整数，$a\_1,a\_2 \cdots a\_n.$

第三行$m$个整数，$b\_1,b\_2 \cdots b\_m.$

$1 \leq a\_i,b\_i \leq 10^5$

# Standard Output

输出一个整数，方师傅可以最多赚得的美分数目。

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
<tr><td>5 5 100000 1000
1 2 3 4 5
3 2 4 5 1</td><td>3</td></tr><tr><td>3 4 3006 1000
1 2 3
1 2 4 3</td><td>2</td></tr></table>


# Constraints



# Note



# Source


