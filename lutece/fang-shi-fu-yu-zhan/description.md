
# Content

方师傅有一个$1-N$的排列，排列的顺序是固定的，他想要把这个排列重新排列成他喜欢的顺序。

于是他买了一个栈，他会按顺序将排列扔进栈内，在某些时刻将栈顶元素取出，这样出栈后的排列就可以重新排序啦。

例如，原序列是$1$,$2$，他先将$1$入栈，再将$2$入栈，然后将$2$出栈，最后将$1$出栈，那么新序列就变成了$2$,$1$。

方师傅很好奇，当前排列能不能通过一个栈变成他想要的排列呢？

# Standard Input

输入第$1$行包含$1$个数字$N$，代表方师傅的排列的长度。

接下来$1$行包含$N$个整数，代表最开始方师傅的排列。

接下来$1$行包含$N$个整数，代表方师傅想要的排列。

$N \leq 1000000$

# Standard Output

输出包含$1$个字符串`Yes`或者`No`，代表方师傅能否成功

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
3 2 1
1 2 3</td><td>Yes</td></tr><tr><td>4
1 2 3 4
3 1 2 4</td><td>No</td></tr></table>


# Constraints



# Note



# Source


