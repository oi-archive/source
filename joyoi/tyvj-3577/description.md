# 

 
 # 题目描述 
<p>
给一个n*m地图，计算从(n,1)【注：左下角】到第x列的第y行的路径条数mod k，走过的点不能再走，转弯只能向右转。<br></p> 

 
 # 输入格式 
<p>
第一行输入n m k<br>第二行输入x y,注意这里是x列Y行<br>以下n行m行的字符矩阵<br>+表示可以走，*表示障碍。<br></p> 

 
 # 输出格式 
<p>
答案 mod k<br></p> 
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
<tr><td>3  5  10 
4  2 
+++++ 
++*++ 
++++* 

</td><td>2 </td></tr></table>
