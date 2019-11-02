# 

 
 # 题目背景 
[noip2003P2]数字游戏 

 
 # 题目描述 
丁丁最近沉迷于一个数字游戏之中。这个游戏看似简单，但丁丁在研究了许多天之后却发觉原来在简单的规则下想要赢得这个游戏并不那么容易。游戏是这样的，在你面前有一圈整数（一共n个），你要按顺序将其分为m个部分，各部分内的数字相加，相加所得的m个结果对10取模后再相乘，最终得到一个数k。游戏的要求是使你所得的k最大或者最小。<BR>例如，对于下面这圈数字（n=4，m=2）：<BR><img src="/source/joyoi/tyvj-1901/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTkwMS8mbmJzcDtodHRwOi8veXQudHl2ai5jbjo4MDgwL1Byb2JsZW1JbWcvUDEwMzUuanBn.jpg" border=0 align=middle><BR>当要求最小值时，((2-1)&nbsp;mod&nbsp;10)×((4+3)&nbsp;mod&nbsp;10)=1×7=7，要求最大值时，为((2+4+3)&nbsp;mod&nbsp;10)×(-1&nbsp;mod&nbsp;10)=9×9=81。特别值得注意的是，无论是负数还是正数，对10取模的结果均为非负值。<BR>丁丁请你编写程序帮他赢得这个游戏。<BR> 

 
 # 输入格式 
输入文件第一行有两个整数，n（1≤n≤50）和m（1≤m≤9）。以下n行每行有个整数，其绝对值不大于104，按顺序给出圈中的数字，首尾相接。 

 
 # 输出格式 
输出文件有两行，各包含一个非负整数。第一行是你程序得到的最小值，第二行是最大值。<BR><BR> 
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
<tr><td>4 2
4
3
-1
2
</td><td>7
81
</td></tr></table>
