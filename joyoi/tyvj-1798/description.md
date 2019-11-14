# 

 
 # 题目背景 
2007年江苏省省选第二试 

 
 # 题目描述 
超太空实验室现在需要切割出一块多边形金属板。现有的材料是一块宽n米，高m米的母板，4角的坐标是(0,0)-(0,m)-(n,m)-(n,0)。所需要的金属板最多有8个顶点。受切割工具所限制，只能沿着直线将现有的一块板剪穿，即你不能剪一半，或者沿着曲线切割。<BR>	例如，n=m=100，需要切割出一块四边形(80,80),(70,30),(20,20),(20,80)。下图表示了最佳的切割方案（即切割长度最短）。图中粗线旁的数字标明了切割的顺序。<BR><img src="/source/joyoi/tyvj-1798/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTc5OC9Qcm9ibGVtSW1nLzE3OTguYm1w.bmp" border=0 align=middle> 

 
 # 输入格式 
第一行是两个整数，n和m，0&lt;n,&nbsp;m&lt;=500。<BR>	第二行是p，表示目标多边形的边数，3&lt;=p&lt;=8。<BR>	接下来每行一个坐标(x,&nbsp;y)，(x,&nbsp;y)位于母板的内部（不在边上）。顶点是按照顺时针的顺序给出的。<BR> 

 
 # 输出格式 
按照样例格式输出最短的切割长度，精确到3位小数。(等号两边都有一空格)。 

 
 # 提示 
2007年江苏省省选第二试 
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
<tr><td>100 100
4
80 80
70 30
20 20
20 80
</td><td>Minimum total length  =  312.575</td></tr></table>
