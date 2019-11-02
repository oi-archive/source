# 

 
 # 题目描述 
<p>在衡二，众所周知，所有的电子设备是一律禁物。但是总是有小强以身犯险，atttx123很荣幸的成为其中的一员。在每天13个小时的埋头苦学之后，他总要抽出一点点时间在被窝里搞自己的电子词典，小强atttx123很强悍地依然去玩那HANOI（汉诺塔），话说他玩了很长很长时间了呢&hellip;&hellip;<br />
<br />
对于汉诺塔问题，大家一定很熟悉。给定A,B,C三根足够长的细柱，在A柱上放有n个中间有圆孔的圆盘，且从下向上半径依次减小，共有n个不同的尺寸(下图为n=4的情形)。现要将&nbsp;这些圆盘移到C柱上，在移动过程中可放在B柱上暂存。<br />
<br />
<img src="/source/joyoi/tyvj-2906/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL3R5dmotMjkwNi9wcm9ibGVtc19pbWFnZXMvMzQ3Mi9wZy5qcGc=.jpg" /><br />
因为他的电子词典的特殊性，这个游戏要有新的要求：<br />
(1)每次只能移动一个圆盘，且只能移动到相临的柱子上；<br />
(2)&nbsp;A、B、C三根细柱上的圆盘都要保持上小下大的顺序；<br />
(3)每移动一次步数加一；<br />
(4)A柱上的盘子向左移动则到达C柱，C柱上的盘子向右移动则到达A柱；<br />
atttx123很喜欢玩这个游戏，以至于要立志每天玩完1盘，他的电子词典向右移动按钮失灵了（谁叫他光玩呢&mdash;&darr;&mdash;），于是他想正常的Hanoi塔游戏对于n个盘则最少步数An为2n-1，那么只用向左移动键玩，则对于n个盘最小步数An是多少？<br />
他要估计自己玩完一盘到底要多少时间~~~~~。</p> 

 
 # 输入格式 
<p>输入为一个正整数n&nbsp;(0&le;n&le;1000)，表示在A柱上放有n个圆盘。</p> 

 
 # 输出格式 
<p>输出仅一行，包含一个正整数，为完成上述任务所需的最少移动次数An（保证&nbsp;An&le;10^1000）。</p> 

 
 # 提示 
<p>【数据范围】<br />
0&lt;=30%&lt;=30<br />
0&lt;=100%&lt;=1000</p> 
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
<tr><td>1</td><td>1</td></tr></table>
