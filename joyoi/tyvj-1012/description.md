# 

 
 # 题目背景 
NOIP2008年提高组第二题<BR> 

 
 # 题目描述 
给你n根火柴棍，你可以拼出多少个形如“A+B=C”的等式？等式中的A、B、C是用火柴棍拼出的整数（若该数非零，则最高位不能是0）。用火柴棍拼数字0-9的拼法如图所示：<BR><img src="/source/joyoi/tyvj-1012/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTAxMi9Qcm9ibGVtSW1nL3AxMDEyLmdpZg==.gif" border=0 align=middle><BR>注意：<BR>1.&nbsp;加号与等号各自需要两根火柴棍<BR>2.&nbsp;如果A≠B，则A+B=C与B+A=C视为不同的等式（A、B、C&gt;=0）<BR>3.&nbsp;n根火柴棍必须全部用上<BR> 

 
 # 输入格式 
输入文件matches.in共一行，又一个整数n（n&lt;=24）。 

 
 # 输出格式 
输出文件matches.out共一行，表示能拼成的不同等式的数目。 

 
 # 提示 
【输入输出样例1解释】<BR>2个等式为0+1=1和1+0=1。<BR>【输入输出样例2解释】<BR>9个等式为：<BR>0+4=4<BR>0+11=11<BR>1+10=11<BR>2+2=4<BR>2+7=9<BR>4+0=4<BR>7+2=9<BR>10+1=11<BR>11+0=11<BR> 
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
<tr><td>【输入样例1】 
14
【输入样例2】 
18</td><td>【输出样例1】 
2
【输出样例2】 
9</td></tr></table>
