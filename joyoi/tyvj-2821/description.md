# 

 
 # 题目描述 
<p>
有一列整数，共n个。每次可以对这些整数操作，有两种操作：<br>1 第i个到第j个整数分别加上数p<br>2 询问这些数中比t小的数的个数。<br></p> 

 
 # 输入格式 
<p>
第一行有两个数，n和m(1<=n<=100000,m<=10,000)，表示数的个数和操作数。<br>第二行n个整数，表示每个数的初始值。<br>以后m行，每行开始一个数q。<br>若q为1,则后面跟三个数i，j (i<=j)，表示两个下标； p(-1000=p<=1000)，表示修改的数。<br>若q为2，则为询问操作，后面跟一个数t。<br><br></p> 

 
 # 输出格式 
<p>
对每个询问操作输出数列中比t小的个数。</p> 

 
 # 提示 
<p>
对于100％的数据，1<=n<=100,000，1<=m<=10,000</p> 
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
<tr><td>5 3
1 2 3 4 5
2 0
1 1 5 -10
2 0
</td><td>0
5</td></tr></table>
