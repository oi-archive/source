# 

 
 # 题目背景 
&nbsp;Yours和zero在研究A*启发式算法.拿到一道经典的A*问题,但是他们不会做,请你帮他们. 

 
 # 题目描述 
在3×3的棋盘上，摆有八个棋子，每个棋子上标有1至8的某一数字。棋盘中留有一个空格，空格用0来表示。空格周围的棋子可以移到空格中。要求解的问题是：给出一种初始布局（初始状态）和目标布局（为了使题目简单,设目标状态为123804765），找到一种最少步骤的移动方法，实现从初始布局到目标布局的转变。&nbsp; 

 
 # 输入格式 
输入初试状态，一行九个数字，空格用0表示 

 
 # 输出格式 
只有一行，该行只有一个数字，表示从初始状态到目标状态需要的最少移动次数(测试数据中无特殊无法到达目标状态数据) 
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
<tr><td>283104765</td><td>4</td></tr></table>