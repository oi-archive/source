# 

 
 # 题目描述 
<p>
<img border="0" src="/source/joyoi/tyvj-2604/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjYwNC9wcm9ibGVtc19pbWFnZXMvMzA0Ni8xNzczLmpwZw==.jpg"></p> 

 
 # 输入格式 
<p>
* 第1行: 三个由空格隔开的正数: N, M1和M2<br><br>* 第2到1+M1行: 第i+1行表示第i条单向道路，包含两个由空格隔开的整数: A_i和B_i<br><br>* 第2+M1到第1+M1+M2行: 第i+M1+1行表示第i条单向道路，包含两个由空格隔开的整数<br>	X_i和Y_i<br><br></p> 

 
 # 输出格式 
<p>
* 第1到M2行: 第i行应该包含两个由空格隔开的整数: 根据你给第i条双向道路定义的的方<br>	向，可能是X_i, Y_i，也可能是Y_i, X_i。这些双向道路必须按照输入的顺序<br>	输出。如果无解，在单独的一行内输出"-1"。<br><br></p> 
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
<tr><td>4 2 3
1 2
4 3
1 3
4 2
3 2
</td><td>1 3
2 4
2 3
</td></tr></table>
