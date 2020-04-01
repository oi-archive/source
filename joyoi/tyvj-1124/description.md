# 

 
 # 题目背景 
&nbsp;&nbsp;&nbsp;&nbsp;xq和他的老婆xz最近开了一家花店，他们准备把店里最好看的花都摆在橱窗里。但是他们有很多花瓶，每个花瓶都具有各自的特点，因此，当各个花瓶中放入不同的花束时，会产生不同的美学效果。为了使橱窗里的花摆放的最合适，他们得想个办法安排每种花的摆放位置。<BR>&nbsp;&nbsp;&nbsp;&nbsp;可是因为xq和xz每天都太忙，没有时间设计橱窗里花的摆法，所以他们想让你帮他们求出花摆放的最大美观程度和每种花所放的位置。<BR>&nbsp;&nbsp;&nbsp;&nbsp;<BR><BR> 

 
 # 题目描述 
&nbsp;&nbsp;&nbsp;&nbsp;每种花都有一个标识，假设杜鹃花的标识数为1，秋海棠的标识数为2，康乃馨的标识数为3，所有的花束在放入花瓶时必须保持其标识数的顺序，即：杜鹃花必须放在秋海棠左边的花瓶中，秋海棠必须放在康乃馨左边的花瓶中。如果花瓶的数目大于花束的数目。则多余的花瓶必须空置，且每个花瓶中只能放一束花。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;每种花放在不同的瓶子里会产生不同的美观程度，美观程度可能是正数也可能是负数。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;上述例子中，花瓶与花束的不同搭配所具有的美观程度，如下表所示：<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;花&nbsp;&nbsp;&nbsp;&nbsp;瓶<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;&nbsp;&nbsp;&nbsp;4&nbsp;&nbsp;&nbsp;&nbsp;5<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1&nbsp;(杜鹃花)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;7&nbsp;&nbsp;&nbsp;&nbsp;23&nbsp;&nbsp;&nbsp;-5&nbsp;&nbsp;-24&nbsp;&nbsp;&nbsp;16<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2&nbsp;(秋海棠)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;&nbsp;21&nbsp;&nbsp;&nbsp;-4&nbsp;&nbsp;&nbsp;10&nbsp;&nbsp;&nbsp;23<BR>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3&nbsp;(康乃馨)&nbsp;&nbsp;&nbsp;&nbsp;-21&nbsp;&nbsp;&nbsp;&nbsp;5&nbsp;&nbsp;&nbsp;-4&nbsp;&nbsp;-20&nbsp;&nbsp;&nbsp;20<BR><BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;根据上表，杜鹃花放在花瓶2中，会显得非常好看；但若放在花瓶4中则显得十分难看。<BR><BR>&nbsp;&nbsp;&nbsp;&nbsp;为取得最大美观程度，你必须在保持花束顺序的前提下，使花束的摆放取得最大的美学值，并求出每种花应该摆放的花瓶的编号。 

 
 # 输入格式 
第1行：两个整数F和V，表示xq和xz一共有F种花，V个花瓶。(1&lt;=F&lt;=V&lt;=100)<BR>第2行到第F+1行：每行有V个数，表示花摆放在不同花瓶里的美观程度值value。(美观程度和不超过maxint，美观程度有正有负。)<BR> 

 
 # 输出格式 
输出有两行：第一行为输出最大美观程度和的值，第二行有F个数表示每朵花应该摆放的花瓶的编号。 

 
 # 提示 
其实就是简单的DP，花店橱窗问题啦。<BR>注意尽量靠前放啊!<BR> 
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
<tr><td>3 5 
7 23 -5 -24 16
5 21 -4 10 23
-21 5 -4 -20 20</td><td>53
2 4 5</td></tr></table>
