# 

 
 # 题目背景 
清北学堂TYVJ9月模拟赛试题第三题 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;给一个N*N的数字矩阵，我们定义最左上的格子为(1,1)最右下的格子为(N,N)。现在从(1,1)出发，每次只能往下一格或者往右一格，到达(N,N)。<BR>&nbsp;&nbsp;&nbsp;&nbsp;要求一路上所有数的乘积的十进制表示下，末尾的0的个数最少。<BR>&nbsp;&nbsp;&nbsp;&nbsp;且路径中不能经过数值是0的点。 

 
 # 输入格式 
第一行一个数N。<BR>接下来N行，每行N个数，来描述这个矩阵。<BR>矩阵的所有元素都是非负的。<BR> 

 
 # 输出格式 
一个数，表示最少的0的个数，保证肯定有解。 

 
 # 提示 
数据规模<BR>对于30%&nbsp;的数据&nbsp;N≤250。<BR>对于100%&nbsp;的数据&nbsp;1≤N≤1&nbsp;000。 
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
1 3 0 0
0 8 2 25
6 5 0 3
0 15 7 4</td><td>2</td></tr></table>
