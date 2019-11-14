# 

 
 # 题目描述 
<p>Ural大学有N个职员，编号为1~N。他们有从属关系，也就是说他们的关系就像一棵以校长为根的树，父结点就是子结点的直接上司。每个职员有一个快乐指数。现在有个周年庆宴会，要求与会职员的快乐指数最大。但是，没有职员愿和直接上司一起与会。</p> 

 
 # 输入格式 
<p>第一行一个整数N。(1&lt;=N&lt;=3000)<br />
接下来N行，第i+1行表示i号职员的快乐指数Ri。(-128&lt;=Ri&lt;=127)<br />
接下来N-1行，每行输入一对整数L,K。表示K是L的直接上司。<br />
最后一行输入0,0。</p> 

 
 # 输出格式 
<p>输出最大的快乐指数。</p> 
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
<tr><td>7
1
1
1
1
1
1
1
1 3
2 3
6 4
7 4
4 5
3 5
0 0</td><td>5</td></tr></table>
