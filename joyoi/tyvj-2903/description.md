# 

 
 # 题目描述 
<p>
对于无向图G,它的任一棵生成树T的权值P(t)定义为T的所有边权的最大公约数。<br>对于给定的图G，求出其所有生成树T1,T2……的权值P(T1),P(T2)……的最小公倍数。</p> 

 
 # 输入格式 
<p>
第一行 N M 表示图G的点数，边数。<br>接下来M行 Si Ti Di 描述一条边（Si,Ti）权值为 Di。<br>保证图连通，无自环。<br></p> 

 
 # 输出格式 
<p>
一个数，所有生成树权值的最小公倍数。</p> 

 
 # 提示 
<p>
样例解释<br>有3棵生成树，权值分别为1,2,3,它们的最小公倍数为6。<br><br>数据约定<br>20%   M=N-1<br>30%   M=N<br>100%  N<=1000  M<=100000  Di<=2^15-1  Ans<=2^64-1<br>保证极限数据很少。<br> <br></p> 
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
<tr><td>3 3
1 2 2 
2 3 3 
1 3 6
</td><td>6</td></tr></table>
