# 题目描述


<h3>
【题目描述】
</h3>
<p>
一些摩天大楼被沿着直线修建。摩天大楼的数量是2到314!（314的阶乘，一个很大的数）之间的一个随机整数。每栋大楼的高度独立地随机选取，对任意正整数i，有2^(-i)的概率高度为i。高度为i的大楼的楼层从0到i-1编号。
</p>
<p>
为了加快运输速度，在大楼之间安装了一些溜索。特别地，在某栋楼的i层和另一栋楼的i层之间有一条溜索，当且仅当这两栋楼之间没有一栋有i层的大楼。
</p>
<p>
Alice和Bob决定数一数摩天大楼的数量。
</p>
<p>
Alice十分细心，她想知道到底有多少栋摩天楼。她从最左侧的摩天大楼开始，计数器为1.然后她向右移动，每次移到下一栋大楼，并将计数器加1.她持续移动，直到到达最右侧的摩天楼。
</p>
<p>
Bob非常没耐心，他希望尽快结束。他从最左侧的摩天大楼开始，计数器为1.他使用溜索在大楼之间一栋。每次Bob都用最高的溜索向右移动，但由于恐高，他会忽略掉那些编号超过h的楼层。Bob用溜索旅行得如此之快，以至于他根本没法数清经过了多少大楼。因此他只是将计数器加上2^i，其中i是他当前所在的楼层编号。他持续移动，直到到达最右侧的摩天楼。
</p>
<p>
考虑如下例子。有6栋大楼，从左到右的高度分别是1,4,3,4,1,2，且h=2。Alice开始时计数器为1，并且将计数器加了五次1，得到的结果是6.Bob开始时计数器为1，然后他依次加上1,4,4,2，最终得到12.注意，Bob出于恐高忽略掉了最高的溜索。
</p>
<p>
<img src="/upload/image/20150326/20150326113611_67121.png" alt=""/> 
</p>
<p>
Bob的计数器在图片顶部，Alice的计数器在图片底部。所有溜索都已画出。Bob的路径是绿色虚线，Alice的路径是粉色虚线。所有楼层都被标号，Bob经过的溜索旁写出了Bob向计数器上加的数。
</p>
<p>
当Alice和Bob到达最右端的摩天楼时，他们将各自的计数器拿出来比较。给出Alice或者Bob的计数器的值，你需要计算出另外一个人的计数器的期望值。
</p>
<h3>
【输入格式】
</h3>
<p>
第一行一个名字，是字符串&#34;Alice&#34;或&#34;Bob&#34;。第二行包含两个整数n和h（2&lt;=n&lt;=30000,0&lt;=h&lt;=30）。
</p>
<p>
如果名字是&#34;Alice&#34;，n就代表Alice到达最右端摩天楼时，她的计数器的值。否则n就代表Bob到达最右端摩天楼时计数器的值。h代表Bob愿意到达的最高楼层。
</p>
<h3>
【输出格式】
</h3>
<p>
一行一个实数，即另一个人计数器的期望值。
</p>
<p>
保留到小数点后九位。
</p>
<h3>
【样例输入输出】
</h3>
<div class="sample-test">
<div class="input">
<div class="title">
Input
</div>
<pre>Alice
3 1
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>3.500000000
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>Bob
2 30
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>2
</pre>
</div>
<div class="input">
<div class="title">
Input
</div>
<pre>Alice
2572 10
</pre>
</div>
<div class="output">
<div class="title">
Output
</div>
<pre>3439.031415943</pre>
</div>
</div>
<h3>
【来源】
</h3>
<p>
<a href="http://codeforces.com/problemset/problem/335/E" target="_blank">CODEFORCES 335E</a> 
</p>
