# 

 
 # 题目描述 
是不是平时在手机里玩吃豆豆游戏玩腻了呢？最近MOKIA手机上推出了一种新的围豆豆游戏，大家一起来试一试吧。<BR><BR>游戏的规则非常简单，在一个N×M的矩阵方格内分布着D颗豆子，每颗豆有不同的分值Vi。游戏者可以选择任意一个方格作为起始格，每次移动可以随意的走到相邻的四个格子，直到最终又回到起始格。最终游戏者的得分为所有被路径围住的豆豆的分值总和减去游戏者移动的步数。矩阵中某些格子内设有障碍物，任何时刻游戏者不能进入包含障碍物或豆子的格子。游戏者可能的最低得分为0，即什么都不做。<BR><BR>注意路径包围的概念，即某一颗豆在路径所形成的多边形（可能是含自交的复杂多边形）的内部。下面有两个例子（见图片）：<BR><img src="/source/joyoi/tyvj-1778/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTc3OC9odHRwOi8veXQudHl2ai5jbjo4MDgwL1Byb2JsZW1JbWcvUDEyMjIuanBn.jpg" border=0 align=middle><BR>&nbsp;<BR>第一个例子中，豆在路径围成的矩形内部，所以豆被围住了。第二个例子中，虽然路径经过了豆的周围的8个格子，但是路径形成的多边形内部并不包含豆，所以没有围住豆子。<BR>布布最近迷上了这款游戏，但是怎么玩都拿不了高分。聪明的你决定写一个程序来帮助他顺利通关。<BR> 

 
 # 输入格式 
第一行两个整数N和M，为矩阵的边长。<BR>第二行一个整数D，为豆子的总个数。<BR>第三行包含D个整数V1到VD，分别为每颗豆子的分值。<BR>接着N行有一个N×M的字符矩阵来描述游戏矩阵状态，0表示空格，#表示障碍物。而数字1到9分别表示对应编号的豆子。<BR> 

 
 # 输出格式 
包含一个整数，为最高可能获得的分值。 

 
 # 提示 
50%的数据满足1≤D≤3。<BR>100%的数据满足1≤D≤9，1≤N,&nbsp;M≤10，-10000≤Vi≤10000。<BR>四川SCOI2009二试&nbsp;第三题 
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
<tr><td>3 8
3
30 -100 30
00000000
010203#0
00000000
</td><td>38
</td></tr></table>
