# 题目描述


<h3>
【题目描述】
</h3>
<p>
你有一个n*m的矩形网格。一些格子中已经涂上了k种颜色中的某些颜色。你需要给所有未染色格子用这k种颜色染色，使得任意一条从左上角到右下角的路径都不包含两个同色格子。路径只能向右或向下。
</p>
<p>
输出答案模1000000007（10^9+7）的值。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行包含三个整数n,m,k（1&lt;=n,m&lt;=1000,1&lt;=k&lt;=10）。接下来的n行每行包含m个整数，表示了网格的这一行。0代表相应的格子未被染色，否则就是这个格子已被染上的颜色，颜色是一个1~k的正整数。
</p>
<h3>
【输出格式】
</h3>
<p>
输出一行一个整数，代表可能的染色方案数模10^9+7的值。
</p>
<h3>
【样例输入】
</h3>
<div class="sample-test">
<div class="input">
<div class="title">
Input
</div>
<pre>2 2 4
0 0
0 0
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>48
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>2 2 4
1 2
2 1
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
<pre>5 6 10
0 0 0 0 0 0
0 0 0 0 0 0
0 0 0 0 0 0
0 0 0 0 0 0
0 0 0 0 0 0
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>3628800
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>2 6 10
1 2 3 4 5 6
0 0 0 0 0 0
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>4096</pre>
</div>
</div>
<h3>
【来源】
</h3>
<p>
<a href="http://codeforces.com/problemset/problem/293/B" target="_blank">CODEFORCES 293B</a> 
</p>
