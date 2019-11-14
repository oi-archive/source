# 

 
 # 题目描述 
<p>
给出平面上的两个点集,如果其中一个点集可以通过扩大、缩小、旋转、翻转、移动等操作变换到另一个点集,那么我们就称这两个点集相似,个例子: 点集{(0,0), (2,0), (2,1)} 和点集{(6,1), (6,5), (4,5)}相似,但是不和点集4,0),(6,0), (5,-1)}相似.给出点集求他们是否相似.</p> 

 
 # 输入格式 
<p>
第一行一个数k (1 <= k <= 25.000) – 表示第一个点集的点的个数.接下来k 行每行描述一个点: x_i i y_i (-20.000 <= x_i, y_i <= 20.000). 不存在两点坐标相同. 接下来一个数: n (1 <= n <= 20).表示有多少个点集要检测, 接下来 n 个点集的描述, 和上面相同. <br></p> 

 
 # 输出格式 
<p>
对于每个要测试的点集,如果它和第一个点集相似那么打印TAK (YES in Polish), 否则打印NIE (NO in Polish) . <br></p> 
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
0 0
2 0
2 1
2
3
4 1
6 5
4 5
3
4 0
6 0
5 -1
</td><td>TAK
NIE</td></tr></table>
