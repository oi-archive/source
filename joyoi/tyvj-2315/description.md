# 

 
 # 题目描述 
<p>
给出无向图G(V, E). 每次操作任意加一条非自环的边(u, v), 每条边的选择是等概率的. 问使得G连通的期望操作次数. (|V| <= 30, |E| <= 1000)<br></p> 

 
 # 输入格式 
<p>
第一行两个整数N,M<br>1<=N<=30<br>0<=M<=1000<br>接下来M行,每行两个整数X,Y表示两者之间已修好一条道路.<br>两点之间可以不止修了一条路,也有可能M条路已使N个点成为一个整体.<br><br></p> 

 
 # 输出格式 
<p>
输出一个小数,表示新修道路条数的期望值,保留六位小数.</p> 
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
<tr><td>4 2
1 2 
3 4
</td><td>1.500000</td></tr></table>
