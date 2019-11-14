# 

 
 # 题目描述 
<p>
一个骑士在一个无限的棋盘上移动. 每个移动都可以用一对数(a,b) 描述表示可以从棋盘上的点(x,y) 到 (x+a,y+b) 或 (x-a,y-b) . 每个骑士都有一系列的移动. 每个移动可以在任意时候使用任意次数. <br>我们说两个骑士是等价,当且仅当这两个骑士从(0,0)出发到达的点完全一样. 可以知道对于任意骑士都可以找出找出一个和他等价的且只包含两个移动的骑士. 求这个骑士的两个移动. <br></p> 

 
 # 输入格式 
<p>
第一行一个整数n 表示骑士的移动个数, 3 <= n <= 100. 接下来n 每行两个整数a_i 和 b_i 表示一个移动, -100 <= a_i, b_i <= 100. 我们可以假设(a_i,b_i) <> (0,0). <br></p> 

 
 # 输出格式 
<p>
输出两行表示对应的两个移动. <br></p> 
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
<tr><td>3
24 28
15 50
12 21
</td><td>468 1561
2805 9356
or: 	
3 0
0 1</td></tr></table>
