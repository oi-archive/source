# 

 
 # 题目描述 
<p>
给你两个数列A=(a1,a2,a3,…,an)和B=(b1,b2,b3,…,bm)，把ai (1<=i<=n)和bj (1<=j<=m)乘起来，得到一个新的有m*n个数的数列。把这个序列排列成非递减数列，然后请找出排在第k位的数。</p> 

 
 # 输入格式 
<p>
输入有多组数据。<br>每组数据的第一行包含三个整数：n(1<=n<=10000), m(1<=m<=10000), k(1<=k<=m*n).<br>第二行包含n个整数，表示数列A。<br>第三行包含m个整数，表示数列B。<br>所有数列A和B里的数字范围是 [0, 10000].<br>每组数据之后有一个空行。<br></p> 

 
 # 输出格式 
<p>
每组数据输出一行，为答案。</p> 

 
 # 提示 
<p>
对于所有数据，1<=n<=10000，1<=m<=10000，1<=k<=m*n，0<=ai<=10000, 0<=bj<=10000。</p> 
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
<tr><td>1 3 3
1
3 2 1

3 3 7
1 2 3
1 2 3
</td><td>3
6</td></tr></table>
