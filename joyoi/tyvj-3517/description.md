# 

 
 # 题目描述 
<p>
有一个a*b的整数组成的矩阵，现请你从中找出一个n*n的正方形区域，使得该区域所有数中的最大值和最小值的差最小。<br></p> 

 
 # 输入格式 
<p>
第一行为3个整数，分别表示a,b,n的值<br>第二行至第a+1行每行为b个非负整数，表示矩阵中相应位置上的数。每行相邻两数之间用一空格分隔。<br></p> 

 
 # 输出格式 
<p>
仅一个整数，为a*b矩阵中所有“n*n正方形区域中的最大整数和最小整数的差值”的最小值。<br></p> 
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
<tr><td>5 4 2
1 2 5 6
0 17 16 0
16 17 2 1
2 10 2 1
1 2 2 2
</td><td>1
问题规模
（1）矩阵中的所有数都不超过1,000,000,000
（2）20%的数据2<=a,b<=100,n<=a,n<=b,n<=10
（3）100%的数据2<=a,b<=1000,n<=a,n<=b,n<=100
</td></tr></table>
