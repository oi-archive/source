# 

 
 # 题目描述 
<p>
空间中有N个点，其中第i个点的坐标是(xi, yi, zi)．此外我们为每一个点分配一个权值，第i个点的权是ci． 任何一个过原点(0, 0, 0)的平面，将所有点分成两个部分（正好在平面上的点可以任意选择被放入哪一个部分），选择其中点的权值之和较大的一个部分作为平面的权值．请你找到这样一个平面，其权值最大． <br></p> 

 
 # 输入格式 
<p>
第一行有一个整数N，表示空间中点的个数． <br>以下N行，每行4个整数，xi, yi, zi和ci，描述第i个点的坐标和权值． <br></p> 

 
 # 输出格式 
<p>
输出文件中只包含一个整数，表示所有过原点的平面中最大的权值． <br></p> 

 
 # 提示 
<p>
30%的数据中，1 <= N <= 50 <br>100%的数据中，1 <= N <= 1 000 <br>100%的数据中， |xi|, |yi|, |zi|, |ci| <= 10 000 <br></p> 
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
1 0 0 -4 
-1 0 0 2 
0 1 0 3 
0 -1 0 -5 
0 0 1 5 
0 0 -1 -5 
</td><td>10 </td></tr></table>
