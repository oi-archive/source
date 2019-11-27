
# Content

给定若干线段，线段有起点和终点及一定花费，据说，用若干线段把闭区间[0,T]完全覆盖，就可以召唤神龙，问召唤神龙的最少花费

# Standard Input

多组数据。

首先输入数据组数Cases

对于每组数据，输入N,T，分别为线段个数和闭区间右端点。

接下来有N行，每行包含l,r,c表示线段的左右端点及花费

Cases<=20

1<=N<=1e5

1<=T<=1e9

0<=L<R<=T

1<=C<=1000

# Standard Output

对于每组数据，输出最小花费，如果无法召唤神龙，输出-1

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
3 5
0 3 10
2 5 12
4 5 3
3 5
0 3 10
2 5 12
3 5 3
2 5
0 3 10
4 5 3</td><td>22
13
-1</td></tr></table>


# Constraints



# Note



# Source


