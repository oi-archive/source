# 题目描述


<h3>
【题目描述】
</h3>
<p>
布条游戏是一个双人游戏。游戏需要一张棋盘和三种颜色的矩形布条：红色，绿色和蓝色。所有的红色布条大小都为c*1（这指1行c列，下同），绿色布条是z*1，蓝色布条是m*1，其中c,z,n都是整数。每名玩家都有无限数量的三种布条。
</p>
<p>
棋盘是一个大小为p*1的矩形，包含p个1*1的小方格。
</p>
<p>
玩家轮流移动。每次移动，玩家在棋盘上放置一块任意颜色的布条。有一些规则必须遵守：
</p>
<p>
·布条不能超出棋盘范围。
</p>
<p>
·不能覆盖（甚至不能部分覆盖）先前放置的布条。
</p>
<p>
·布条的两端必须和方格的（竖直）边重合。无法按规则移动的玩家输。
</p>
<p>
先手指第一个移动的玩家。我们说先手必胜，如果无论后手（即第二个移动的玩家）做出如何移动，先手都能赢。
</p>
<p>
请你写一个程序判断先手是否有必胜策略。
</p>
<h3>
【输入格式】
</h3>
<p>
输入文件的第一行有三个空格隔开的整数c,z,n（1&lt;=c,z,n&lt;=1000），分别代表红，绿，蓝三种颜色布条的长度。
</p>
<p>
第二行有一个整数m（1&lt;=m&lt;=1000），代表需要考虑的不同棋盘数量。
</p>
<p>
第3行到第m+2行每行有一个整数p（1&lt;=p&lt;=1000）.第i+2行的整数代表第i张棋盘的长度。
</p>
<h3>
【输出格式】
</h3>
<p>
输出应当包含m行。
</p>
<p>
第i行应当只有一个整数：
</p>
<p>
·1——如果第i张棋盘的先手必胜。
</p>
<p>
·2——其他情况。
</p>
<h3>
【样例输入】
</h3>
<pre>1 5 1
3
1
5
6</pre>
<h3>
【样例输出】
</h3>
<pre>1
1
2</pre>
<h3>
【来源】
</h3>
<p>
<a href="http://www.oi.edu.pl/old/php/show.php?ac=e181313&amp;module=show&amp;file=zadania/oi7/paski" target="_blank">POI 2000 Stipes</a> 
</p>