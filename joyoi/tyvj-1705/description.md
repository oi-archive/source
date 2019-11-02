# 

 
 # 题目背景 
石家庄二中&nbsp;真理检验杯NOIP模拟赛&nbsp;第四题&nbsp;2011.8<BR> 

 
 # 题目描述 
GF画了一棵有n(1&lt;=N&lt;=1000)个节点的树，每个节点i(1&lt;=i&lt;=n)都有一个权值Ai(1&lt;=Ai&lt;=1000)。现在GF要把这棵树的节点全部染成粉色（Oh&nbsp;My&nbsp;Pink~）。染色的规则是：根节点R可以随时被染色；对于其他节点，在被染色之前它的父亲节点必须已经被染上了色。每次染色的代价为T*A[i]，其中T代表当前是第几次染色。求把这棵树全部染成粉色的最小总代价。 

 
 # 输入格式 
第一行两个整数N和R，表示树的节点个数和根节点编号，接下来N行每行一个整数Ai，表示第i个节点的权值。接下来N-1行每行两个整数x，y，表示x是y的父亲。 

 
 # 输出格式 
一个数，表示染色的最小总代价。 

 
 # 提示 
Poj2054 
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
<tr><td>5 1
1 2 1 2 4
1 2
1 3
2 4
3 5
</td><td>33</td></tr></table>
