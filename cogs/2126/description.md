# 题目描述


<h3>
【题目描述】
</h3>
<p>
a180285幸运地被选做了地球到喵星球的留学生。他发现喵星人在上课前的点名现象非常有趣。   假设课堂上有N个喵星人，每个喵星人的名字由姓和名构成。喵星球上的老师会选择M个串来点名，每次读出一个串的时候，如果这个串是一个喵星人的姓或名的子串，那么这个喵星人就必须答到。 然而，由于喵星人的字码过于古怪，以至于不能用ASCII码来表示。为了方便描述，a180285决定用数串来表示喵星人的名字。现在你能帮助a180285统计每次点名的时候有多少喵星人答到，以及M次点名结束后每个喵星人答到多少次吗？  
</p>
<h3>
【输入格式】
</h3>
<p>
现在定义喵星球上的字符串给定方法：先给出一个正整数L，表示字符串的长度，接下来L个整数表示字符串的每个字符。输入的第一行是两个整数N和M。接下来有N行，每行包含第i 个喵星人的姓和名两个串。姓和名都是标准的喵星球上的字符串。接下来有M行，每行包含一个喵星球上的字符串，表示老师点名的串。
</p>
<h3>
【输出格式】
</h3>
<p>
对于每个老师点名的串输出有多少个喵星人应该答到。然后在最后一行输出每个喵星人被点到多少次。
</p>
<h3>
【样例输入】
</h3>
<pre>2 3
6 8 25 0 24 14 8 6 18 0 10 20 24 0
7 14 17 8 7 0 17 0 5 8 25 0 24 0
4 8 25 0 24
4 7 0 17 0
4 17 0 8 25
</pre>
<h3>
【样例输出】
</h3>
<pre>2
1
0
1 2
</pre>
<h3>
【数据范围】
</h3>
<pre>对于30%的数据，保证：1&lt;=N,M&lt;=1000，喵星人的名字总长不超过4000，点名串的总长不超过2000。
对于100%的数据，保证：1&lt;=N&lt;=50000，1&lt;=M&lt;=100000，喵星人的名字总长和点名串的总长分别不超过200000，
保证喵星人的字符串中作为字符存在的数不超过10000。 </pre>
<pre>数据范围已修正 by rapiz 2017/3/12</pre>
<h3>
【来源】
</h3>
<p>
上传 &amp; 加强 by stdafx
</p>
