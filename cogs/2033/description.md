# 题目描述


<h3>
【题目描述】
</h3>
<p>
给一个无向图图，如果存在欧拉回路请从第一个点为起点开始遍历，如果存在欧拉路，则以字典序大的为起点开始遍历，在遍历的过程中，字典序小的先遍历,都不存在输出-1。<span style="background-color:#337FE5;">注意两个点之间可能有多条边，请全部遍历，还有可能存在自环。</span> 
</p>
<h3>
【输入格式】
</h3>
<p>
第一行N,E为点数和边数，后E行每行有两个数，表示他们之间存在一条无向边。
</p>
<h3>
【输出格式】
</h3>
<p>
若干个数，表示遍历次序。
</p>
<h3>
【样例输入】
</h3>
<pre><p>
3 2
</p>

<p>
1 2
</p>

<p>
2 3<span style="font-family:monospace;"></span> 
</p>
</pre>
<h3>
【样例输出】
</h3>
<pre>3 2 1</pre>
<h3>
【提示】
</h3>
<p>
ACM上那道题的修正和加强。<img src="http://cojs.tk/kindeditor/plugins/emoticons/images/41.gif" border="0" alt=""/> N&lt;=20 E&lt;=500
</p>
<h3>
【来源】
</h3>
<p>
HZOI 2015. by stdafx.
</p>
