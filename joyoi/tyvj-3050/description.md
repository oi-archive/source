# 

 
 # 题目描述 
<p>
哥斯拉集齐了七龙珠，召唤出神龙。你很难想象哥斯拉看到神龙的时候有多么惊讶。<br>“你可以许一个愿望。”神龙说。<br>“我要财富。”哥斯拉说。<br>“太没技术含量了，换一个愿望吧。”神龙皱起眉头。<br>“我要换一副英俊的面容。”<br>“你的上一个愿望是什么？”神龙没想到哥斯拉提出这么困难的愿望，心生后悔。<br>“……”<br>“好吧，赐你财富！”<br>神龙使出魔法，在空地上画出一大块N×N（1≤N≤200）的方格，每个格子上写着-10^6到10^6之间的数字。<br>神龙说：“在方格上朝一个方向上行走，可以是行的方向、列的方向或斜对角的方向，一步只能走一格，所有你踩过的数字和就是你的财富。”<br>哥斯拉请你来帮忙，找到一行、一列或一条对角线上的一段连续数字，使它们的和最大。由于神龙方格的神奇特性，沿着一个方向走，走到边际再一步跨过去可以“绕”到方格的对边出现。一行两端的格子是相邻的，甚至相邻两行的不同端的格子也是相邻的（斜对角方向）。<br>对于下图左边的方格，所有标记过的数字都在一条对角线上。<br><br><br><img src="/source/joyoi/tyvj-3050/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMzA1MC9wcm9ibGVtc19pbWFnZXMvMzY3MS8xLnBuZw==.png"></img><br><br>对于这个方格，能踩出的最大的和是24，踩过的数字在右图中标记出来了。</p> 

 
 # 输入格式 
<p>
第一行输入N，之后输入N行N列的矩阵。</p> 

 
 # 输出格式 
<p>
输出最大的和。</p> 
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
<tr><td>4
8 6 6 1
-3 4 0 5
4 2 1 9
1 -9 9 -2
</td><td>24</td></tr></table>
