# 

 
 # 题目背景 
广州市2011年市选第二试 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;你试图在直多边形（一个边都以90度或270度相交，而且内部没有洞的多边形）的基础上，一层层地增加新边框，在新的边框多围出来的区域涂上不同的颜色，以取得特殊的装饰效果。增加的边框与上一层增加的边框（第一层边框则是与直多边形的边）的距离都保持一个固定值d，如下图所示：<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;<img src="/source/joyoi/tyvj-1501/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTUwMS9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvcDE1MDEtMS5ibXA=.bmp" border=0 align=middle><BR>&nbsp;&nbsp;&nbsp;&nbsp;在图左的例子，在直多边形（灰色）的基础上加了两层边框，图3右的例子直多边形形状更复杂些，增加的边框离断成了两部分。注意边框也许离断成若干部分但绝不相交或重叠，即不会发生以下情况：<BR>&nbsp;&nbsp;&nbsp;&nbsp;<img src="/source/joyoi/tyvj-1501/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTUwMS9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvcDE1MDEtMi5ibXA=.bmp" border=0 align=middle><BR>&nbsp;&nbsp;&nbsp;&nbsp;图不会发生的情况<BR>&nbsp;&nbsp;&nbsp;&nbsp;你的任务是计算每层增加的边框长度及每层边框多围出来的面积。<BR> 

 
 # 输入格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行是用空格分隔的三个正整数n,m,d。n是直多边形的边数，m是需要增加边框的层数，n&lt;=100，m&lt;=20，d是边框之间的距离。接下来的若干行，以顺时针方向描述直多边形的n个顶点坐标，每个坐标含空格分隔的两个正整数x和y。第一个顶点坐标满足y坐标最大；如果有多个满足此要求的顶点，我们从当中x坐标最小的开始。<BR> 

 
 # 输出格式 
&nbsp;&nbsp;&nbsp;&nbsp;第一行包含m个整数，按次序输出每层增加的边框长度。<BR>&nbsp;&nbsp;&nbsp;&nbsp;第二行包含m个整数，按次序输出每层边框多围出来的面积。<BR> 
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
<tr><td>6 2 10
20 30 100 30 100 0 0 0 0 10 20 10
3000 3800 
</td><td>340 420
380 2660
</td></tr></table>
