# 

 
 # 题目描述 
<p>
区间（intervals.pas/c/cpp）<br><br>【问题描述】<br><br><br>给定n个封闭的整数区间[ai, bi] (i=1,2,...,n)和n个整数c1, ..., cn。<br>编写一个程序：<br>计算一个最少点数的点集Z，使得Z在第i个区间中的点的数量至少为ci，i=1,2,...,n。<br></p> 

 
 # 输入格式 
<p>
第一行包括一个整数n (1 <= n <= 50000)，表示区间的数量。<br>接下来n行每行包括三个整数，ai，bi，ci，其中0 <= ai <= bi <= 50000，1 <= ci <= bi - ai+1。<br></p> 

 
 # 输出格式 
<p>
输出一个整数，表示点集Z中点的数量。</p> 

 
 # 提示 
<p>
本题数据已经更新完整。<br>选手AC后不妨也到<a href="http://poj.org/problem?id=1201">POJ1201</a>提交！</p> 
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
3 7 3
8 10 3
6 8 1
1 3 1
10 11 1
</td><td>6</td></tr></table>
