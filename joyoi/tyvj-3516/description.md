# 

 
 # 题目描述 
<p>
对于一个给定的S={a1,a2,a3,…,an},若有P={ax1,ax2,ax3,…,axm},满足(x1<x2<…<xm)且（ax1<ax2<…<axm)。那么就称P为S的一个上升序列。如果有多个P满足条件，那么我们想求字典序最小的那个。<br>任务<br>给出S序列，给出若干询问。对于第i个询问，求出长度为Li的上升序列，如有多个，求出字典序最小的那个（即首先x1最小，如果不唯一，再看x2最小……），如果不存在长度为Li的上升序列，则打印Impossible.<br></p> 

 
 # 输入格式 
<p>
第一行一个N，表示序列一共有N个元素<br>第二行N个数，为a1,a2,…,an<br>第三行一个M，表示询问次数。下面接M行每行一个数L，表示要询问长度为L的上升序列。<br></p> 

 
 # 输出格式 
<p>
对于每个询问，如果对应的序列存在，则输出，否则打印Impossible.<br></p> 
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
<tr><td>6
3 4 1 2 3 6
3
6
4
5
</td><td>Impossible
1 2 3 6
Impossible
数据范围
N<=10000
M<=1000</td></tr></table>
