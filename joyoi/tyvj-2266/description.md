# 

 
 # 题目描述 
<p>
在信号处理中，人们有时会对一个给定表达式的最大值感兴趣。这个表达式只含有二进制AND和OR运算，变量都为整数且有一定的取值范围。请你编写程序，求出一个给定表达式的最大值。<br>为了简化题目，这里只考虑一种特殊的表达式，它有若干个由AND连接的子表达式构成，而每个子表达式内只含有OR运算。这样，一个表达式可以由它的子表达式数量和每个表达式内变量的个数唯一确定。例如，(3,1,2,2)表示的表达式为<br>E=(v1 OR v2 OR v3) AND (v4) AND (v5 OR v6) and (v7 OR v8)<br></p> 

 
 # 输入格式 
<p>
第一行为两个整数N和P，其中N为变量的个数(1≤N≤100)，P为子表达式的个数(1≤P≤N)。<br>第二行为P个整数K1,K2,…,KP，其中Ki表示第i个子表达式的变量个数(Ki≥1，SigmaKi=N(1<=i<=N) 。<br>接下来N行，每行两个整数Aj和Bj，表示变量vj的取值范围为[Aj,Bj](0≤Aj≤Bj≤2000000000)。<br></p> 

 
 # 输出格式 
<p>
一个整数，为表达式的最大值。<br></p> 
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
<tr><td>8 4
3 1 2 2
2 4
1 4
0 0
1 7
1 4
1 2
3 4
2 3
</td><td>6</td></tr></table>
