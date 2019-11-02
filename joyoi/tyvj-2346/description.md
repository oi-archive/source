# 

 
 # 题目描述 
<p>
初始有N堆火柴，第i堆大小为Ai。<br>两个人轮流取火柴，每次最多可以在m堆里取，取走火柴的总数必须大于0.<br>谁无法取谁输。问谁有必胜策略<br></p> 

 
 # 输入格式 
<p>
 第一行一个整数T(T<=10)，表示数据个数<br> 解下来包括T组数据，每组数据第一行两个整数n,m（n<=500，m<=100）<br> 之后n行，每行一个整数ai（ai<=10^50），描述某一行的火柴数<br></p> 

 
 # 输出格式 
<p>
按输入顺序对每一组数据输出答案。<br>若先手肯定会输，则输出一个数0；否则输出1</p> 
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
0</td></tr></table>
