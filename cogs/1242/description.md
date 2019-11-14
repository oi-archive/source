# 题目描述


<h3>
【题目描述】
</h3>
<p>
<span style="font-size:16px;">做了HEOI2012的赵州桥(bridge)之后，liouzhou_101就感到极其的不爽，首先那题题目叙述巨渣，然后做法极坑。</span> 
</p>
<p>
<span style="font-size:16px;">不过那题是一道和染色有关的问题，于是在此同时也启发liouzhou_101想到了这样一个简单的问题：</span> 
</p>
<p>
<span style="font-size:16px;">在一串未打结的项链上(意思就是说项链的左端和右端不相连)，有N颗珠子，你有M种颜色，然后就问你有多少种方法将每一颗珠子都染上颜色，使得任意两颗相邻的珠子的颜色不同。</span> 
</p>
<p>
<span style="font-size:16px;">liouzhou_101这种傻×自然不会做了，于是来向你请教…</span> 
</p>
<p>
<span style="font-size:16px;">当然，由于liouzhou_101的脑子构造极其简单，你不要想太多，请不要考虑Polya之类的本质相同，否则的话仅凭liouzhou_101的理解能力是不能理解的…</span> 
</p>
<h3>
【输入格式】
</h3>
<p>
输入只有一行，三个正整数N、M和P，之间以一个空格隔开。
</p>
<h3>
【输出格式】
</h3>
<p>
输出只有一行，表示染色的方法总数模P。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
5 4 13
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre><p>
12
</p>
</pre>
<h3>
【提示】
</h3>
<p>
样例注释：
</p>
<p>
    一共有324种染色方法，对13取模后是12。
</p>
<p>
数据范围：
</p>
<p>
对于10%的数据，N=1，M&lt;=10，P&lt;=10；
</p>
<p>
对于20%的数据，N&lt;=10，M&lt;=10，P&lt;=100；
</p>
<p>
对于50%的数据，N,M,P&lt;=1,000,000,000；
</p>
<p>
对于100%的数据，1&lt;=N,M,P&lt;=1,000,000,000,000,000,000，且M&gt;=2。
</p>
<h3>
【来源】
</h3>
<p>
<a href="http://www.tyvj.cn/Problem_Show.aspx?id=2043" target="_blank">http://www.tyvj.cn/Problem_Show.aspx?id=2043</a> 
</p>
