# 题目描述


<p align="left">
<b>[问题描述]</b> 
</p>
<p align="left">
    你将要游览一个有 <strong><em>N </em></strong>个岛屿的公园。从每一个岛 <em>i </em>出发 ，只建造一座 桥。桥的长度以 <strong><em>Li </em></strong>表示。公园内总共有 <strong><em>N </em></strong>座桥。 尽管每座桥由一个岛连到另一个岛，但每座桥均可以双向行走。同时，每一对这样的岛屿，都有一艘专用的往来两岛之间的渡船。
</p>
<p>
相对于乘船而言，你更喜欢步行。 你希望所经过的桥的总长度尽可能的长，但受到以下的限制。
</p>
<p>
可以自行挑选一个岛开始游览。
</p>
<ul>
<li>
任何一个岛都不能游览一次以上。
</li>
<li>
无论任何时间你都可以由你现在所在的岛<em>S </em>去另一个你<strong>从未</strong>到过的岛 <em>D </em>。由 <em>S </em>到 <em>D </em>可以有以下方法：
<ul>
<li>
步行：仅当两个岛之间有一座桥时才有可能。对于这种情况，桥的长度会累加到你步行的总距离；或者
</li>
<li>
渡船：你可以选择这种方法，仅当没有任何桥 和/或 以前使用过的渡船的组合可以由 <em>S </em>走到 <em>D </em>（当检查是否可到达时 ，你应该考虑所有的路径，包括经过你曾游览过的那些岛）。
</li>
</ul>
</li>
</ul>
<p>
注意，你不必游览所有的岛，也可能无法走完所有的桥。
</p>
<p align="left">
<br/>
<strong>任务 </strong> 
</p>
<p>
编写一个程序，给定 <strong><em>N </em></strong>座桥以及它们的长度，按照上述的规则，计算你可以走过的桥的最大长度。
</p>
<p>
<strong>限制 </strong> 
</p>
<p>
2 &lt;= <strong><em>N </em></strong>&lt;= 1,000,000 公园内的岛屿数目。
</p>
<p>
1&lt;= <strong><em>Li </em></strong>&lt;= 100,000,000 桥 <strong><em>i </em></strong>的长度。
</p>
<p>
<strong>输入 </strong> 
</p>
<p>
你的程序要从输入文件读入以下数据：
</p>
<ul>
<li>
第一行包含 <strong><em>N </em></strong>个整数，即公园内岛屿的数目。岛屿由 1 到 <strong><em>N </em></strong>编号。
</li>
<li>
随后的 <strong><em>N </em></strong>行每一行用来表示一个岛。第 <strong><em>i </em></strong>行由两个以单空格分隔的整数，表示由岛 <strong><em>i </em></strong>筑的桥。第一个整数表示桥另一端的岛，第二个整数表示该桥的长度 <strong><em>Li </em></strong>。你可以假设对於每座桥，其端点总是位于不同的岛上 。
</li>
</ul>
<p>
<strong>输出 </strong> 
</p>
<p>
你的程序必须向输出文件写出包含一个整数的单一行，即可能的最大步行距离。
</p>
<p>
<strong>注</strong>：对某些测试，答案可能无法放进 32-bit 整数，你要取得这道题的满分，可能需要用 Pascal 的 int64 或 C/C++ 的 long long 类型。
</p>
<p>
<strong>评分 </strong> 
</p>
<p>
有总计 40 分的测试数据，其中 <strong><em>N </em></strong>不会超过 4,000 。
</p>
<p>
<strong>样例输入</strong> 
</p>
<pre>7
3 8
7 2
4 2
1 4
1 9
3 4
2 3
</pre>
<p>
<strong>样例输出</strong> 
</p>
<pre>24
</pre>
<p>
<strong>提示</strong> 
</p>
<img src="http://www.lydsy.com/JudgeOnline/images/1791.jpg" border="0"/>
