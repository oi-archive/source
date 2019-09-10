# 题目描述


<h2>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【题目描述】</span>
</h2>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span> 
</p>
<p>
	黑白棋游戏的棋盘是由4*4的方格阵列构成。棋盘的每一方格中放有1枚棋子，共有8枚白棋子和8枚黑棋子。这16枚棋子的每一种放置方案都构成一个游戏状态。在棋盘上拥有1条公共边的2个方格称为相邻方格。一个方格最多可有4个相邻方格。在玩黑白棋游戏时，每一步可将任何2个相邻方格中棋子互换位置。对于给定的初始游戏状态和目标游戏状态，编程计算从初始游戏状态变化到目标游戏状态的最短着棋序列。
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输入格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"></span> 
</p>
<p style="text-indent:21.0000pt;">
	输入文件共8行。前四行是初始游戏状态，后四行是目标游戏状态。每行四个数分别表示该行放置的棋子颜色。“0”表示白棋，“1”表示黑棋。
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【输出格式】</span> 
</h3>
<p>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;"><span style="font-size:15.833333015441895px;line-height:20px;">输出文件的第一行是着棋步数n。接下来n行，每行4个数分别表示该步交换棋子的两个相邻方格的位置。例如，abcd表示棋盘上（a，b）处的棋子与（c，d）处的棋子换位。</span></span> 
</p>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输入】</span> 
</h3>
<pre>1111
0000
1110
0010
1010
0101
1010
0101</pre>
<h3>
	<span style="font-family:&#39;Microsoft YaHei&#39;;font-size:16px;">【样例输出】</span> 
</h3>
<pre>4
1222
1424
3242
4344</pre>
