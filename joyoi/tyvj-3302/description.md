# 

 
 # 题目描述 
<p>
Problem 4 : matrix<br>矩阵乘法<br><br>问题描述：<br>　　一个A x B的矩阵乘以一个B x C的矩阵将得到一个A x C的矩阵，时间复杂度为A x B x C。矩阵乘法满足结合律（但不满足交换律）。顺序给出n个矩阵的大小，请问计算出它们的乘积的最少需要花费多少时间。<br><br></p> 

 
 # 输入格式 
<p>
　　第一行输入一个正整数n，表示有n个矩阵。<br>　　接下来m行每行两个正整数Xi,Yi，其中第i行的两个数表示第i个矩阵的规模为Xi x Yi。所有的Xi、Yi <= 100。输入数据保证这些矩阵可以相乘。<br><br></p> 

 
 # 输出格式 
<p>
　　输出最少需要花费的时间。<br><br></p> 

 
 # 提示 
<p>
样例说明：<br>　　顺序计算总耗时7500；先算后两个总耗时75000。<br><br>时间限制：<br>　　各测试点1秒。<br><br>内存限制：<br>　　你的程序将被分配32MB的运行空间。<br><br>数据范围：<br>　　n <= 100。</p> 
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
<tr><td>3
10 100
100 5
5 50

</td><td>7500
</td></tr></table>
