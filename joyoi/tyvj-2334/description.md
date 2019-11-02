# 

 
 # 题目描述 
<p>
考虑一个多项式(x2 + x + 1)^n. 我们对展开式中的系数ci 很感兴趣:<br>C0 + C1x + C2x^2 + ... + C2n x^2n<br>举个例子, (x^2 + x + 1)^3 = 1 + 3x + 6x^2 + 7x^3 + 6x^4 + 3x^5 + x^6.<br></p> 

 
 # 输入格式 
<p>
第一行一个数k 表示数据的组数, 1 <= k <= 10000. 然后接下来k 组数据, 每组两个非负整数n 和 i, 0 <= n <= 1000000000000000, 0 <= i <= 2n. <br></p> 

 
 # 输出格式 
<p>
对于每组数据，输出ci 模3 以后的结果. <br></p> 
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
<tr><td>5
2 0
7 4
4 5
5 3
8 15
</td><td>1
2
1
0
2</td></tr></table>
