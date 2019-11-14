# 

 
 # 题目描述 
<p>&nbsp;&nbsp;&nbsp;&nbsp;有N个排成一排的方格，每个方格上有一个棋子，棋子可能是白色或者黑色。<br />
&nbsp;&nbsp;&nbsp;&nbsp;方格旁边有M个按键，每个按键上有两个数字(i,j)，表示此按键可以交换第i个格子和第j个格子上的棋子，这个操作所需时间为|i-j|+1。<br />
&nbsp;&nbsp;&nbsp;&nbsp;现在给出各个按键、起始状态和结束状态，要求算出从起始状态变成结束状态最少需要用的时间。</p> 

 
 # 输入格式 
<p>&nbsp;&nbsp;第一行一个正整数N，表示有N个方格。(1&lt;=N&lt;=100)<br />
&nbsp;&nbsp;接下来两个只包含01的长度为N的数字串S1,S2。<br />
&nbsp;&nbsp;字符串第I位对应第I个方格，0表示该方格棋子为白色，1表示该方格位黑色。<br />
&nbsp;&nbsp;第四行一个正整数M，表示有M个按键。(1&lt;=M&lt;=200)<br />
&nbsp;&nbsp;接下来M行，每行两个正整数(i,j)，表示此按键可以交换第i个和第j个方格上的棋子。(1&lt;=i,j&lt;=N)</p> 

 
 # 输出格式 
<p>&nbsp;&nbsp;&nbsp;若无法通过现有按键将起始状态变换结束状态，输出&#39;Impossible&#39;（不用输出引号），否则输出最少需要的时间。</p> 

 
 # 提示 
<p>EZ_gx</p> 
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
<tr><td>4
1010
1001
5
1 1
2 4
4 1
2 3
2 1
</td><td>5
</td></tr></table>
