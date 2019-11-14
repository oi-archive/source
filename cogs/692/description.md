# 题目描述


<strong>USACO 2012 March Contest Silver Divison</strong><br/>
Problem 1. Tractor 拖拉机<br/>
<br/>
<em>Translated by <a target="_blank" href="http://www.yeefan.tk/">Makazeu</a></em><br/>
在一天的工作结束之后，农夫John完全忘记了他的拖拉机——他把他的拖拉机落在了田野的中央。<br/>
他的奶牛永远都不怀好意（up to no good），决定跟FJ玩个恶作剧：<br/>
他们在田地里的很多地方堆积了一共N捆干草，所以FJ在不先移除(remove)这些干草堆的情况下无法很容易的移走(remove)他的拖拉机。<br/>
<br/>
<br/>
<p>
	这个拖拉机的位置，和这N(1&lt;=N&lt;=50000)个干草堆的位置都在一个二维平面内，用1～1000的整数坐标来描述。
</p>
<p>
	没有一个干草的位置在拖拉机的初始位置(initial position)。
</p>
<p>
	当FJ驾驶着他的拖拉机时，他仅能平行于坐标轴(parallel to the coordinate axes，东、西、南、北)移动，
</p>
<p>
	而且他必须按照整数序列移动(move in a sequence of integer amounts)。
</p>
<p>
	例如，他可以向南移动2个单位，然后向东移动3个单位。拖拉机不能移动到有干草堆的位置。
</p>
<p>
	请帮助FJ决定一下他最少需要移走多少干草堆才能使他自由的移走他的拖拉
</p>
<p>
	机（也就是说，他能把他的拖拉机移动到平面坐标系的原点。译者补充：可以先移动到边界以外，然后绕到原点）
</p>
<br/>
程序名：tractor<br/>
<br/>
输入格式：<br/>
*第一行：三个用空格分隔开的整数：N，和拖拉机的起始位置(starting location)x,y。<br/>
*第2～1+N行：每行包括两个整数(x,y)表示每个干草堆的位置。<br/>
<br/>
<br/>
输入样例(file tractor.in):<br/>
7 6 3<br/>
6 2<br/>
5 2<br/>
4 3<br/>
2 1<br/>
7 3<br/>
5 4<br/>
6 4<br/>
<br/>
<br/>
输入解释：<br/>
拖拉机开始在(6,3)。一共有7堆干草，分别位于(6,2)，(5,2)，(4,3)，(2,1)，(7,3)，(5,4)和(6,4)。<br/>
<br/>
<br/>
输出格式：<br/>
*第一行：最小移走干草堆的数。<br/>
<br/>
<br/>
输出样例(file tractor.out):<br/>
1<br/>
<br/>
<br/>
输出解释：<br/>
FJ只需要移走一堆干草即可移走他的拖拉机。<br/>
