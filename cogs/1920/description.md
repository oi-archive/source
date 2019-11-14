# 题目描述


<h3>
【题目描述】
</h3>
<p>
Piegirl最终找到了红色按钮。你只有最后一次机会来改变必然的结局。
</p>
<p>
按钮下的电路包含n个节点，从0到n-1编号。为了让按钮失效，你需要按照特定的顺序来拆除这n个节点。节点0必须被最先拆除。在拆除节点i后，下一个被拆除的节点必须是(2*i) mod n或者(2*i+1) mod n。最后一个被拆除的节点必须是0.节点0必须被拆除两次，但其他节点必须被拆除恰好一次。
</p>
<p>
你的任务是找到任意一个可行的拆除顺序并输出它。如果没有这样的方案，输出-1.
</p>
<h3>
【输入格式】
</h3>
<p>
一行一个整数n（2&lt;=n&lt;=10^5）。
</p>
<h3>
【输出格式】
</h3>
<p>
输出拆除所有节点的顺序。如果这是不可能的，就输出-1.如果有多种不同的顺序，输出任意一种。
</p>
<h3>
【样例输入输出】
</h3>
<div class="sample-test">
<div class="input">
<div class="title">
Input
</div>
<pre>2
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>0 1 0
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>3
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>-1</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>4
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>0 1 3 2 0
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>16
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>0 1 2 4 9 3 6 13 10 5 11 7 15 14 12 8 0</pre>
</div>
</div>
<h3>
【来源】
</h3>
<p>
<a href="http://codeforces.com/problemset/problem/325/E" target="_blank">CODEFORCES 325E</a> 
</p>
