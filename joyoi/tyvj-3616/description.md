# 

 
 # 题目描述 
<p>
维护一个W*W的矩阵，每次操作可以增加某格子的权值，或询问某子矩阵的总权值。<br>修改操作数M<=160000，询问数Q<=10000，W<=2000000。<br></p> 

 
 # 输入格式 
<p>
</p> 

 
 # 输出格式 
<p>
</p> 

 
 # 提示 
<p>
Input file	Output file	Meaning<br>0 4		Table size is  , filled with zeroes.<br><br>1 2 3 3		Add 3 customers at (2, 3).<br>2 1 1 3 3		Query sum of rectangle  ,  .<br><br>	3	Answer.<br>1 2 2 2		Add 2 customers at (2, 2).<br>2 2 2 3 4		Query sum of rectangle  ,  .<br><br>	5	Answer<br>3		Exit your program.<br></p> 
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
<tr><td>0 4
1 2 3 3
2 1 1 3 3
1 2 2 2
2 2 2 3 4
3
</td><td>
3
5
</td></tr></table>
