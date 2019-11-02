# 

 
 # 题目背景 
有一天TsyD来到了一个花园~ 

 
 # 题目描述 
现在有一个花园，被分割成了几个部分，要求在上面种M种花，且有公共边的区域不能是同种花（否则两个区域就没有区分了啊。。。。。废话。。。）求有多少种方案。<BR>因为各家的花园各不相同，但大多数都是这样的三种形状：<BR>图1：<BR><img src="/source/joyoi/tyvj-1201/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTIwMS9Qcm9ibGVtSW1nLzEyMDEtMS5qcGc=.jpg" border=0 align=middle><BR>P&nbsp;=&nbsp;0（一个横行）<BR>图2：<BR><img src="/source/joyoi/tyvj-1201/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTIwMS9Qcm9ibGVtSW1nLzEyMDEtMi5qcGc=.jpg" border=0 align=middle><BR>P&nbsp;=&nbsp;1（一个环形）<BR>图3：<BR><img src="/source/joyoi/tyvj-1201/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTIwMS9Qcm9ibGVtSW1nLzEyMDEtMy5qcGc=.jpg" border=0 align=middle><BR>P&nbsp;=&nbsp;2（环形中间多了个区域） 

 
 # 输入格式 
就一行&nbsp;N,Color,P&nbsp;（N代表一共几块区域，color代表一共有多少种颜色的花，P代表第几个图形） 

 
 # 输出格式 
就一行方案总数&nbsp;如果很大请MOD&nbsp;11129 

 
 # 提示 
数据范围<BR>序号	N		Color	&nbsp;P<BR>1	&lt;=10		&lt;=10	&nbsp;0<BR>2	&lt;=1000		&lt;=100	&nbsp;0<BR>3	&lt;=999		&lt;=99	&nbsp;0<BR>4	&lt;=1000000	&lt;=1000	&nbsp;0<BR>5	&lt;=1000000000	&lt;=100000&nbsp;0<BR>6	&lt;=10		&lt;=10	&nbsp;1<BR>7	&lt;=100		&lt;=100	&nbsp;1<BR>8	&lt;=1000000	&lt;=50	&nbsp;1<BR>9	&lt;=100		&lt;=100	&nbsp;2<BR>10	&lt;=1000000	&lt;=50	&nbsp;2<BR> 
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
<tr><td>三组样例：
Input1:	3 4 0
Input2:	4 5 1
Input3:	5 6 2</td><td>分别对应三组输入：
Output1	36
Output2:260
Output3:1560</td></tr></table>
