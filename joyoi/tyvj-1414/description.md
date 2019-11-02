# 

 
 # 题目背景 
JerryZhou同学经常改编习题给自己做。<BR>这天，他又改编了一题。。。。。<BR> 

 
 # 题目描述 
设有N*N的方格图，我们将其中的某些方格填入正整数，<BR>而其他的方格中放入0。<BR>某人从图得左上角出发，可以向下走，也可以向右走，直到到达右下角。<BR>在走过的路上，他取走了方格中的数。（取走后方格中数字变为0）<BR>此人从左上角到右下角共走3次，试找出3条路径，使得取得的数总和最大。<BR> 

 
 # 输入格式 
第一行:N&nbsp;&nbsp;&nbsp;(4&lt;=N&lt;=20)<BR>接下来一个N*N的矩阵，矩阵中每个元素不超过80，不小于0 

 
 # 输出格式 
一行，表示最大的总和。<BR> 

 
 # 提示 
多进程DP 
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
<tr><td>4
1 2 3 4
2 1 3 4
1 2 3 4
1 3 2 4
</td><td>39
</td></tr></table>
