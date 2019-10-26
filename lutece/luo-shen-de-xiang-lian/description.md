
# Content

罗神的项链由三种颜色的珠子组成，罗神每天会取出两枚不同颜色的珠子，变成两枚第三种颜色的珠子。

今天你看到罗神的项链三种颜色的珠子分别有$a,b,c$个，你记起以前看到过罗神的项链则是由$x,y,z$个三种颜色的珠子。

你觉得罗神肯定是重新换了一条项链，因为$x,y,z$肯定没办法变换到$a,b,c$。但是你的感觉究竟对不对呢？你决定写一个程序来计算。

# Standard Input

第一行一个整数$t$($t\leq 100$),表示测试数据的组数。

每组测试数据两行：

第一行三个整数$x,y,z$($0\leq x,y,z\leq 3000$)，第二行三个整数$a,b,c$($0\leq a,b,c\leq 3000$)。

# Standard Output

每组数据输出一个字符串`YES`或者`NO`，`YES`表示罗神可以从$x,y,z$变到$a,b,c$，`NO`表示罗神不可能从$x,y,z$变到$a,b,c$。

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
1 1 0
0 0 2
1 1 0
2 0 0
2 2 2
3 0 3</td><td>YES
NO
YES</td></tr></table>


# Constraints



# Note

`2 2 2->4 1 1->3 0 3`

# Source


