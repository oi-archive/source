# 

 
 # 题目描述 
<p>


 
 # 输入格式 
<p>
第1行： 一个数， N。

 
 # 输出格式 
<p>
第1行： 一个数，把所有牛排好序的最短时间。
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
<tr><td>
3
2
3
1

输入解释：

队列里有三头牛，脾气分别为 2，3， 1。
</td><td>
7

输出解释：
2 3 1 : 初始序列
2 1 3 : 交换脾气为3和1的牛(时间=1+3=4). 
1 2 3 : 交换脾气为1和2的牛(时间=2+1=3). 