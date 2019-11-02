# 

 
 # 题目描述 
<p>
    Tony和Mary中午吃完饭后闲着无聊，决定玩游戏打发时间。<br>    两人商量之后决定了游戏规则如下：<br>1、	初始时有n堆火柴<br>2、	两人轮流取火柴<br>3、	每次可以从最多m堆中取走任意多个，但取走火柴的总数必须大于0<br>4、	谁无法取火柴了（即没有火柴了）谁就输了<br>Tony和Mary都是无敌聪明的人，所以两人每次取火柴时都不会犯错误。<br>但火柴的数量实在是太多了，Tony决定编个程序自动帮他取，你帮帮他吧。<br></p> 

 
 # 输入格式 
<p>
    第一行一个整数T(T<=10)，表示数据个数<br>    解下来包括T组数据，每组数据第一行两个整数n,m（n<=500，m<=100）<br>    之后n行，每行一个整数ai（ai<=10^50），描述某一行的火柴数<br></p> 

 
 # 输出格式 
<p>
    按输入顺序对每一组数据输出答案。<br>    若Tony和Mary肯定会输，则输出一个数0；否则输出1<br></p> 
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
<tr><td>2
2 1
10
11
2 1
10000
10000
</td><td>1
0</td></tr></table>
