# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2249/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjI0OS9wcm9ibGVtc19pbWFnZXMvMjYxNS8xMzI3LmpwZw==.jpg"><br>游戏的棋盘是一个“井”字形棋盘，总共24个格子，这24个格子分别有8个1，8个2，8个3，每一次，你可以选择A,B,C,D,E,F,G,H这8个方向的一个方向旋转一格（具体旋转例子参见上图），使得最后最中间的8个格子上的数值相同。<br>现在希望你求出最少的旋转次数<br><br><br></p> 

 
 # 输入格式 
<p>
本题为多组数据<br>每个数据为一行，共24个数，从上到下从左到右依次描述每一个格子。<br>以0表示结束<br><br><br></p> 

 
 # 输出格式 
<p>
输出为一行，若干个由”A”..”H”组成的字母，表示一组解的方案，如果有多组可行解，你需要输出字典序最小的解。<br><br></p> 
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
<tr><td>1 1 1 1 3 2 3 2 3 1 3 2 2 3 1 2 2 2 3 1 2 1 3 3
0


</td><td>AC</td></tr></table>
