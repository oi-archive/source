# 

 
 # 题目背景 
APIO2011T1&nbsp;&nbsp;方格染色 

 
 # 题目描述 
Sam和他的妹妹Sara有一个包含n&nbsp;×&nbsp;m个方格的表格。她们想要将其的每个方格都染成红色或蓝色。出于个人喜好，他们想要表格中每个2&nbsp;×&nbsp;2的方形区域都包含奇数个（1个或3个）红色方格。例如，下图是一个合法的表格染色方案（在打印稿中，深色代表蓝色，浅色代表红色）。<BR><img src="/source/joyoi/tyvj-1732/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTczMi9Qcm9ibGVtSW1nLzE3MzIuanBn.jpg" border=0 align=middle><BR>可是昨天晚上，有人已经给表格中的一些方格染上了颜色！现在Sam和Sara非常生气。不过，他们想要知道是否可能给剩下的方格染上颜色，使得整个表格仍然满足她们的要求。如果可能的话，满足他们要求的染色方案数有多少呢？ 

 
 # 输入格式 
输入的第一行包含三个整数n,&nbsp;m和k，分别代表表格的行数、列数和已被染色的方格数目。<BR>之后的k行描述已被染色的方格。其中第i行包含三个整数xi,&nbsp;yi和ci，分别代表第i个已被染色的方格的行编号、列编号和颜色。ci为1表示方格被染成红色，ci为0表示方格被染成蓝色。 

 
 # 输出格式 
输出一个整数，表示可能的染色方案数目W模10^9得到的值。（也就是说，如果W大于等于10^9，则输出W被10^9除所得的余数）。 

 
 # 提示 
对于20%的测试数据，n,&nbsp;m&nbsp;≤&nbsp;5，k&nbsp;≤&nbsp;5；<BR>对于50%的测试数据，n,&nbsp;m&nbsp;≤&nbsp;5000，k&nbsp;≤&nbsp;25；<BR>对于所有的测试数据，2&nbsp;≤&nbsp;n,&nbsp;m&nbsp;≤&nbsp;10^6，0&nbsp;≤&nbsp;k&nbsp;≤&nbsp;10^6，1&nbsp;≤&nbsp;xi&nbsp;≤&nbsp;n，1&nbsp;≤&nbsp;yi&nbsp;≤&nbsp;m。<BR><BR>此数据为国内数据。 
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
<tr><td>3 4 3
2 2 1
1 2 0
2 3 1</td><td>8</td></tr></table>
