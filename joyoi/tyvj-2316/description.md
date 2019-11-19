# 

 
 # 题目描述 
<p>
有red个红球，blue个蓝球在一个袋子中。两个玩家轮流从袋子中取球，每个人每次可以取1，2或3个球，但在他把球拿出袋子之前，他并不知道所取球的颜色。每次球被取出袋子后，它们的颜色被公布给所有人。取走最后一个红球的人输。现在已知有人在游戏开始前取走了removed个球，并且谁也不知道球的颜色。在两个玩家都采取最优策略时，先手的胜率是多少？<br> 约束条件： 1≤red,blue≤100 , 0≤removed≤red-1。</p> 

 
 # 输入格式 
<p>
一行输入三个数red,blue,removed</p> 

 
 # 输出格式 
<p>
输出胜率,保留16位小数</p> 
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
<tr><td>input 1
1 2 0 

input 2
1 1 0
 
</td><td>output 1
0.3333333333333333

output 2
0.5
 </td></tr></table>
