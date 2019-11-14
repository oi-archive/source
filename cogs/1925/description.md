# 题目描述


<h3>
【题目描述】
</h3>
<p>
Dima喜欢在方格纸上画图，特别地，他有一些格外喜爱的图像。
</p>
<p>
一张大小为n*m的方格纸是一个有n行m列的表格。在空白方格纸上所有格子都是白色的。把方格纸上一些格子涂黑后就得到了一张“图像”。
</p>
<p>
Dima喜爱的图像有如下条件：
</p>
<p>
·图像中包含至少一个黑色格子
</p>
<p>
·所有黑色格子组成一个四连通集，即，你可以从任意黑色格子到达其他全部黑色格子（你可以从一个格子移动到边相邻的黑格）
</p>
<p>
·经过黑色格子从任意黑色格子(x1,y1)到黑色格子(x2,y2)所需要的最小移动步数等于|x1-x2|+|y1-y2|。
</p>
<p>
现在Dima想要知道：有多少种在n*m方格纸上画出他喜爱图像的方案？输出结果模1000000007（10^9+7）的值。
</p>
<h3>
【输入格式】
</h3>
<p>
一行两个正整数n,m，代表方格纸的大小（1&lt;=n,m&lt;=150）.
</p>
<h3>
【输出格式】
</h3>
<p>
一行一个整数，即答案模1000000007（10^9+7）的值。
</p>
<h3>
【样例输入输出】
</h3>
<div class="sample-test">
<div class="input">
<div class="title">
Input
</div>
<pre>2 2
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>13
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>3 4
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>571</pre>
</div>
</div>
<h3>
【来源】
</h3>
<p>
<a href="http://codeforces.com/problemset/problem/273/D" target="_blank">CODEFORCES 273D</a> 
</p>
