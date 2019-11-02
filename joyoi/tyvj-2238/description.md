# 

 
 # 题目描述 
<p>
匪徒准备从一个车站转移毒品到另一个车站,警方准备进行布控. <br>对于每个车站进行布控都需要一定的代价,现在警方希望使用最小的代价控制一些车站,使得去掉这些车站后，匪徒无法从原定的初始点到达目标点</p> 

 
 # 输入格式 
<p>
第一行输入N,M代表车站的总个数,及有多少条双向边连接它们.<br>2<=n<=200 , 1 <=m<=20000.<br>第二行给出两个数a,b,代表匪徒的出发点及目标点.1<=a,b<=N,a<>b.<br>再下来有N行,给出对第i个车站进行布控所需要的Money,其不超过10 000 000<br>再下来M行,用于描述图的结构.</p> 

 
 # 输出格式 
<p>
最少需要多少Money</p> 
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
<tr><td>5 6
5 3
2
4
8
3
10
1 5
1 2
2 4
4 5
2 3
3 4</td><td>
5</td></tr></table>
