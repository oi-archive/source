# 

 
 # 题目描述 
<p>
灾后重建(rebuild)

 
 # 输入格式 
<p>
　　输入文件rebuild.in的第一行包含两个正整数N，M，表示了村庄的数目与公路的长度。

 
 # 输出格式 
<p>
　　输出文件rebuild.out包含Q行，对每一个询问(x, y, t)输出对应的答案，即在第t天，从村庄x到村庄y的最短路径长度为多少。如果在第t天无法找到从x村庄到y村庄的路径，经过若干个已重建完成的村庄，或者村庄x或村庄y在第t天仍未修复完成，则输出-1。

 
 # 提示 
<p>
【数据规模】
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
<tr><td>4 5
1 2 3 4
0 2 1
2 3 1
3 1 2
2 1 4
0 3 5
4
2 0 2
0 1 2
0 1 3
0 1 4


</td><td>-1
-1
5
4
