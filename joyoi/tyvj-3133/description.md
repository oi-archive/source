# 

 
 # 题目描述 
<p>
　　考虑一个N位的二进制串b1…bN，其对应的二进制矩阵为： <br><br><br><center><img src="/source/joyoi/tyvj-3133/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEzMy9wcm9ibGVtc19pbWFnZXMvMTQxNy8xLmJtcA==.bmp"></img></center> 　　　　 <br>　　　　<br>　　然后将这个矩阵的行按照字典顺序排序，'0'在'1'之前。 <br>　　你的任务是编写一个程序，给定排序后的矩阵的最后一列，求出已排序的矩阵的第一行。 <br>　　例如：考虑二进制串（00110），排序后的矩阵为：<br><br><center><img src="/source/joyoi/tyvj-3133/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEzMy9wcm9ibGVtc19pbWFnZXMvMTQxNy8yLmJtcA==.bmp"></img></center> <br>　　　　  <br>　　则该矩阵的最后一列为（1 0 0 1 0）。给出了这一列，你的程序应该确定第一行为（0 0 0 1 1）。 <br></p> 

 
 # 输入格式 
<p>
　　 输入文件名为bincode.in。第一行包含一个整数N(0<=20000)，表示二进制串的位数。第二行包含N个整数，表示已排序的矩阵的最后一列（从上到下）。 </p> 

 
 # 输出格式 
<p>
　　 输出文件名为bincode.out。输出文件仅一行，包含N个整数，从左到右依次表示已排序的矩阵的第一行；若无解，则输出-1。 </p> 
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
<tr><td><br><img src="/source/joyoi/tyvj-3133/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEzMy9wcm9ibGVtc19pbWFnZXMvMTQxNy8zLmJtcA==.bmp"></img></td><td><br><img src="/source/joyoi/tyvj-3133/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzEzMy9wcm9ibGVtc19pbWFnZXMvMTQxNy80LmJtcA==.bmp"></img></td></tr></table>
