# 

 
 # 题目描述 
<p>
给定一个序列{ai | 1 <= ai <= 1000000000 且 1 <= i <= n 且 n <= 15000000}和一个整数 k (k <= n 且 k <= 1000000)，<br>求出a的一个长度为k的子序列{a[bi]}满足：<br>(1)  1 <= b1 <= b2 <= ... <= bk<br>(2) 在满足(1)的情况下 {a[b1], a[b2], ... , a[bk]} 字典序最大。<br></p> 

 
 # 输入格式 
<p>
第一行一个数k<br>以下若干行，且行数大于等于k，为序列ai。<br>以一个单独的0结束<br></p> 

 
 # 输出格式 
<p>
k行，每行一个数，其中第i行为a[bi]。<br></p> 
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
<tr><td>12
5
8
3
15
8
0
</td><td>
12
15
8</td></tr></table>
