# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2643/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjY0My9wcm9ibGVtc19pbWFnZXMvMzA5OC8xODI1XzEuanBn.jpg"> </p> 

 
 # 输入格式 
<p>
<img border="0" src="/source/joyoi/tyvj-2643/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjY0My9wcm9ibGVtc19pbWFnZXMvMzA5OC8xODI1XzMuanBn.jpg"> </p> 

 
 # 输出格式 
<p>
对于每组数据，输出一行。若蔬菜的总价能无限制增大，输出"+inf"（不含引号）。否则输出一个整数，表示所有蔬菜的最大总价。<br> <br></p> 

 
 # 提示 
<p>
<img border="0" src="/source/joyoi/tyvj-2643/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjY0My9wcm9ibGVtc19pbWFnZXMvMzA5OC8xODI1XzIuanBn.jpg"> <br><br>数据规模<br>对 的测试点，保证所有数据都是链，且每个测试点中 的总和不超过 <br>对 的测试点，保证所有数据都是链<br><br>提示<br>若直接用递归DFS整个蔬菜结构，则可能栈溢出。<br></p> 
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
-1 3
1 2
1 1
3 2
3 2
5
-1 3
1 2
1 1
3 2
3 3
0

</td><td>13
+inf
</td></tr></table>
