# 

 
 # 题目背景 
JSOI&nbsp;2009第一试第三题 

 
 # 题目描述 
一个n*m的方格，初始时每个格子有一个整数权值。接下来每次有2种操作：<BR>&nbsp;&nbsp;*改变一个格子的权值；<BR>&nbsp;&nbsp;*求一个子矩阵中某种特定权值出现的个数。 

 
 # 输入格式 
第一行有两个数N,M。<BR>接下来N行，每行M个数，第i+1行第j个数表示格子(i,j)的初始权值。<BR>接下来输入一个整数Q。<BR>之后Q行，每行描述一个操作。<BR>操作1：“1&nbsp;x&nbsp;y&nbsp;c”(不含双引号)。表示将格子(x,y)的权值改成c（1&lt;=x&lt;=n,1&lt;=y&lt;=m,1&lt;=c&lt;=100)。<BR>操作2：“2&nbsp;x1&nbsp;x2&nbsp;y1&nbsp;y2&nbsp;c”(不含双引号，x1&lt;=x2,y1&lt;=y2)。表示询问所有满足格子颜色为c，且x1&lt;=x&lt;=x2,y1&lt;=y&lt;=y2的格子(x,y)的个数。 

 
 # 输出格式 
对于每个操作2，按照在输入中出现的顺序，依次输出一行一个整数表示所求得的个数。 

 
 # 提示 
数据规模：30%的数据，满足：n,m&lt;=30,Q&lt;=50000<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;100%的数据，满足：n,m&lt;=300,Q&lt;=200000 
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
<tr><td>3 3
1 2 3
3 2 1
2 1 3
3
2 1 2 1 2 1
1 2 3 2
2 2 3 2 3 2</td><td>1
2</td></tr></table>
