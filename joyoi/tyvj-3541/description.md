# 

 
 # 题目描述 
<p>
如果一棵树的所有非叶节点都恰好有n个儿子，那么我们称它为严格n元树。如果该树中最底层的节点深度为d（根的深度为0），那么我们称它为一棵深度为d的严格n元树。例如，深度为２的严格２元树有三个，如下图：<br><img border="0" src="/source/joyoi/tyvj-3541/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzU0MS9wcm9ibGVtc19pbWFnZXMvMjM4OC8xLmpwZw==.jpg"><br>给出n, d，编程数出深度为d的n元树数目。<br><br></p> 

 
 # 输入格式 
<p>
仅包含两个整数n, d(0<n<=32, 0<=d<=16)。输入数据保证你不需要考虑某一层多于1024个节点的树（即nd<=1024）。提示：答案保证不超过200位十进制数。<br><br></p> 

 
 # 输出格式 
<p>
仅包含一个数，即深度为d的n元树的数目。<br></p> 
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
<tr><td>【样例输入1】
2 2

【样例输入2】
2 3

【样例输入3】
3 5

</td><td>【样例输出1】
3

【样例输出2】
21

【样例输出2】
58871587162270592645034001</td></tr></table>
