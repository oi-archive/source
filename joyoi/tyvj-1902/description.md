# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;栈是计算机中经典的数据结构，简单的说，栈就是限制在一端进行插入删除操作的线性表。栈有两种最重要的操作，即pop（从栈顶弹出一个元素）和push（将一个元素进栈）。<BR>&nbsp;&nbsp;&nbsp;&nbsp;栈的重要性不言自明，任何一门数据结构的课程都会介绍栈。宁宁同学在复习栈的基本概念时，想到了一个书上没有讲过的问题，而他自己无法给出答案，所以需要你的帮忙。<BR> 

 
 # 题目描述 
<img src="/source/joyoi/tyvj-1902/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTkwMi8mbmJzcDtodHRwOi8veXQudHl2ai5jbjo4MDgwL1Byb2JsZW1JbWcvUDEwMzYtMS5qcGc=.jpg" border=0 align=middle><BR>&nbsp;&nbsp;&nbsp;&nbsp;宁宁考虑的是这样一个问题：一个操作数序列，从1，2，一直到n（图示为1到3的情况），栈A的深度大于n。<BR>&nbsp;&nbsp;&nbsp;&nbsp;现在可以进行两种操作，<BR>&nbsp;&nbsp;&nbsp;&nbsp;1、将一个数，从操作数序列的头端移到栈的头端（对应数据结构栈的push操作）<BR>&nbsp;&nbsp;&nbsp;&nbsp;2、将一个数，从栈的头端移到输出序列的尾端（对应数据结构栈的pop操作）<BR>&nbsp;&nbsp;&nbsp;&nbsp;使用这两种操作，由一个操作数序列就可以得到一系列的输出序列，下图所示为由1&nbsp;2&nbsp;3生成序列2&nbsp;3&nbsp;1的过程。（原始状态如上图所示）你的程序将对给定的n，计算并输出由操作数序列1，2，…，n经过操作可能得到的输出序列的总数。<BR><img src="/source/joyoi/tyvj-1902/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTkwMi8mbmJzcDtodHRwOi8veXQudHl2ai5jbjo4MDgwL1Byb2JsZW1JbWcvUDEwMzYtMi5qcGc=.jpg" border=0 align=middle> 

 
 # 输入格式 
输入文件只含一个整数n（1≤n≤18） 

 
 # 输出格式 
一个整数，即可能输出序列的总数目。 

 
 # 提示 
每点1snoip2003普及组第3题 
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
<tr><td>3</td><td>5</td></tr></table>
