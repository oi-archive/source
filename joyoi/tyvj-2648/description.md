# 

 
 # 题目描述 
<p>
	给定一张有向图，每条边都有一个容量C和一个扩容费用W。这里扩容费用是指将容量扩大1所需的费用。求：

 
 # 输入格式 
<p>
	输入文件的第一行包含三个整数N,M,K，表示有向图的点数、边数以及所需要增加的流量。

 
 # 输出格式 
<p>
	输出文件一行包含两个整数，分别表示问题1和问题2的答案。
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
<tr><td>5 8 2
1 2 5 8
2 5 9 9
5 1 6 2
5 1 1 8
1 2 8 7
2 5 4 9
1 2 1 1
1 4 2 1
</td><td>	13 19
	30%的数据中，N<=100
	100%的数据中，N<=1000，M<=5000，K<=10