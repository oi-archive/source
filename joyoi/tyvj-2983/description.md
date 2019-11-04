# 

 
 # 题目描述 
<p>
小明最近喜欢玩一个游戏。给定一个n * m的棋盘，上面有两种格子#和@。游戏的规则很简单：给定一个起始位置和一个目标位置，小明每一步能向上，下，左，右四个方向移动一格。如果移动到同一类型的格子，则费用是0，否则费用是1。请编程计算从起始位置移动到目标位置的最小花费。</p> 

 
 # 输入格式 
<p>
输入文件有多组数据。

 
 # 输出格式 
<p>
对于每组数据，输出从起始位置到目标位置的最小花费。每一组数据独占一行。</p> 

 
 # 提示 
<p>
对于20%的数据满足：1 < = n, m <= 10。
# 样例数据
<style>
        table,table tr th, table tr td { border:1px solid #0094ff; }
        table { width: 200px; min-height: 25px; line-height: 25px; text-align: center; border-collapse: collapse;}   
    </style>
<table>
	<tr>
		<td>输入样例</td>
		<td>输出样例</td>
	</tr>
<tr><td>2 2
@#
#@
0 0 1 1
2 2
@@
@#
0 1 1 0
0 0
</td><td>2
0</td></tr></table>