# 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;Jimmy最近迷上了一款叫做方块消除的游戏。游戏规则如下：n个带颜色方格排成一列，相同颜色的方块连成一个区域（如果两个相邻方块颜色相同，则这两个方块属于同一区域。游戏时，你可以任选一个区域消去。设这个区域包含的方块数为x，则将得到x^2个分值。方块消去之后，其余的方块就会竖直落到底部或其他方块上。而且当有一列方块被完全消去时，其右边的所有方块就会向左移一格。虽然游戏很简单，但是要拿高分也很不容易。Jimmy希望你能找出得最高分的最佳方案，你能帮助他吗？<BR>&nbsp;&nbsp;&nbsp;&nbsp;具体的决策过程可以看下面的图片：<BR><img src="/source/joyoi/tyvj-1227/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMTIyNy9odHRwOi8vdHl2ai5jcHd6LmNuL1Byb2JsZW1JbWcvMTIyNy5qcGc=.jpg" border=0 align=middle> 

 
 # 输入格式 
第一行包含一个整数n(0&lt;=n&lt;=100)，表示方块数目。第二行包含n个数，表示每个方块的颜色（1到n之间的整数）。 

 
 # 输出格式 
仅一个整数，即最高可能得分。 

 
 # 提示 
IOI2003中国集训队讨论题目 
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
<tr><td>9
1 2 2 2 2 3 3 3 1</td><td>29</td></tr></table>
