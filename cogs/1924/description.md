# 题目描述


<h3>
【题目描述】
</h3>
<p>
Greg有一个平板电脑。这个电脑的屏幕是一个n*m的网格，其中每个方格都是黑色或者白色。我们将网格的行从上到下命名为1~n，类似地将列从左到右命名为1~m。
</p>
<p>
Greg认为平板电脑的屏幕显示出一个洞穴，如果如下两个条件成立：
</p>
<p>
·有一个区间[l,r]（1&lt;=l&lt;=r&lt;=n），使得第l,l+1,...,r行都恰有两个黑格，而其余行全部是白格。
</p>
<p>
·存在一行t，使得对于所有的i,j（l&lt;=i&lt;=j&lt;=t），第i行两个黑格之间的格子组成的集合（包括黑格，下同）是第j行两个黑格之间的格子组成的集合的子集。同样地，对于所有的t&lt;=i&lt;=j&lt;=r，第j行两黑格之间格子组成的集合是第i行两黑格之间格子组成集合的子集。
</p>
<p>
Greg想知道，有多少种在屏幕上显示一个洞穴的方法。两种方法被认为不同，如果在两个图像中某格子的颜色不同。
</p>
<p>
请帮助Greg。
</p>
<h3>
【输入格式】
</h3>
<p>
一行两个整数n,m，代表格子的大小。（1&lt;=n,m&lt;=2000）
</p>
<h3>
【输出格式】
</h3>
<p>
一行一个正整数，即答案模1000000007（10^9+7）的值。
</p>
<h3>
【样例输入输出】
</h3>
<div class="sample-test">
<div class="input">
<div class="title">
Input
</div>
<pre>1 1
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>0
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>4 4
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>485
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>3 5
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>451</pre>
</div>
</div>
<h3>
【来源】
</h3>
<p>
<a href="http://codeforces.com/problemset/problem/295/D" target="_blank">CODEFORCES 295D</a> 
</p>
