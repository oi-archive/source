# 题目描述


<h3>
【英文原题】
</h3>
<p>
Bugs Integrated, Inc. is a major manufacturer of advanced memory chips. They are launching production of a new six terabyte Q-RAM chip. Each chip consists of six unit squares arranged in a form of a 2*3 rectangle. The way Q-RAM chips are made is such that one takes a rectangular plate of silicon divided into N*M unit squares. Then all squares are tested carefully and the bad ones are marked with a black marker.
</p>
<center>
<img src="http://www.poj.org/images/1038/bugs.gif"/> 
</center>
<br/>
Finally, the plate of silicon is cut into memory chips. Each chip consists of 2*3 (or 3*2) unit squares. Of course, no chip can contain any bad (marked) squares. It might not be possible to cut the plate so that every good unit square is a part of some memory chip. The corporation wants to waste as little good squares as possible. Therefore they would like to know how to cut the plate to make the maximum number of chips possible. <br/>
Task <br/>
<p>
You are given the dimensions of several silicon plates and a list of all bad unit squares for each plate. Your task is to write a program that computes for each plate the maximum number of chips that can be cut out of the plate.
</p>
<p>
<br/>
</p>
<h3>
【题目描述】
</h3>
<p>
<br/>
</p>
<p>
给出n*m(n≤150,m≤10)的棋盘，要在上面放置2*3 的骨牌，有一些方格无法放置，求最多能放置多少个。
</p>
<p>
<br/>
</p>
<h3>
【输入格式】
</h3>
<div class="ptx" lang="zh-CN">
<p>
输入包含多组数据。
</p>
<p>
输入文件第一行是数据组数T（T&lt;=50）。
</p>
<p>
接下来是T组数据。
</p>
<p>
每组数据的第一行有三个正数n,m,k，其中k是无法放置骨牌的格子个数。
</p>
<p>
接下来有k行，每行两个整数(x,y)，表示格子(x,y)无法放置骨牌。
</p>
</div>
<h3>
【输出格式】
</h3>
<div class="ptx" lang="zh-CN">
对每组数据，输出一行一个正整数，即最多放置的骨牌个数。<br/>
</div>
<h3>
【样例输入】
</h3>
<pre class="sio">2
6 6 5
1 4
4 6
2 2
3 6
6 4
6 5 4
3 3
6 1
6 2
6 4
</pre>
<h3>
【样例输出】
</h3>
<pre class="sio">3
4</pre>
<h3>
【来源】
</h3>
<div class="ptx" lang="zh-CN">
<a href="searchproblem?field=source&amp;key=CEOI+2002">CEOI 2002</a> 
</div>
<a href="http://www.poj.org/problem?id=1038&amp;lang=zh-CN&amp;change=true"> 北京大学 POJ 1038</a>
