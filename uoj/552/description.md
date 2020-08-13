# 题目描述

<p>出题人 01 买了一只同构判定鸭。一买回来，这只鸭就嘎嘎地叫着：“我是<a href="//uoj.ac/problem/286">同构判定鸡</a>的同类，可以判定两张图是否一样！”</p>
<p>具体来说，同构判定鸭的工作逻辑如下:</p>
<ul><li>给定同构判定鸭两张有向图 $G_1,G_2$，每条边上都写有小写字母。</li>
<li>对于图上的一条路径和一个非空字符串 $S$，我们称这条路径和 $S$ <strong>匹配</strong>当且仅当按照顺序写下路径上所有边的字母所得到的字符串恰好等于 $S$。</li>
<li>定义一个非空字符串 $S$ 在图 $G$ 上的<strong>出现次数</strong>为 $G$ 中与 $S$ 匹配的不同路径条数。</li>
<li>定义一个非空字符串 $S$ 是<strong>好串</strong>，当且仅当其在 $G_1$ 中出现次数和 $G_2$ 中出现次数相等。否则我们称之为坏串。</li>
<li>同构判定鸭判定两张图 $G_1$,$G_2$ <strong>等价</strong>当且仅当所有非空小写字符串 $S$ 都是好串。</li>
</ul><p>但是作为一名有经验的出题人，出题人 01 并不能轻易相信同构判定鸭的结果。</p>
<p>因此他找到你，让你帮他判断两张图是否等价。若不相同，你需要给出长度最短的坏串。若有多个长度最短的坏串，你需要给出其中字典序最小的。</p>
<p>注意本题并不讨论空串的情况。<strong>空串不是好串也不是坏串。</strong></p>

# 输入格式


<p>输入的两部分分别描述 $G_1,G_2$，对于一张图：</p>
<p>第一行两个正整数 $n,m$，表示图的点数和边数。</p>
<p>接下来 $m$ 行，每行两个正整数 $x_i,y_i$ 和一个小写字母 $c_i$，表示一条从 $x_i$ 出发，到 $y_i$ 结束的有向边，边上的字母为 $c_i$。</p>
<p>两张图之间没有额外的空行做分隔。</p>

# 输出格式


<p>若两张图等价，则输出 &#34;<samp>Same</samp>&#34;。</p>
<p>否则按照题目要求输出最短的坏串中字典序最小的。</p>
<p>注意，如果答案是&#34;<samp>Same</samp>&#34;而你输出了&#34;<samp>same</samp>&#34;，你的输出将会被判定为错误。</p>

# 样例一


<h4>input</h4>
<pre>3 3
1 2 a
2 3 b
3 1 c
3 3
1 2 b
2 3 c
3 1 a

</pre>

<h4>output</h4>
<pre>Same

</pre>

<h4>explanation</h4>
<p>将 $G_2$ 中的点按照 $1 \rightarrow 2,2 \rightarrow 3,3 \rightarrow 1$ 重标号后，不难发现其与 $G_1$ 完全相同，自然每个非空小写字符串 $S$ 在两图中的出现次数都相等了。</p>

# 样例二


<h4>input</h4>
<pre>6 6
1 3 a
1 4 a
2 4 b
3 5 a
3 6 b
4 6 b
6 6
1 3 a
1 4 a
2 4 b
3 5 a
4 5 b
4 6 b

</pre>

<h4>output</h4>
<pre>bb

</pre>


# 样例三


<p>见样例数据下载。</p>
<p>该样例范围同测试包 2。</p>

# 样例四


<p>见样例数据下载。</p>
<p>该样例范围同测试包 2。</p>

# 数据范围


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试包编号</th><th>$n$</th><th>$m$</th><th>特殊性质</th><th>分值</th></tr></thead><tbody><tr><td>$1$</td><td>$\le 6$</td><td>$\le 10$</td><td rowspan="2">无</td><td>$15$</td></tr><tr><td>$2$</td><td>$\le 30$</td><td>$\le 100$</td><td>$20$</td></tr><tr><td>$3$</td><td rowspan="2">$\le 100$</td><td rowspan="2">$\le 400$</td><td>保证图是一张有向无环图</td><td>$20$</td></tr><tr><td>$4$</td><td>无</td><td>$15$</td></tr><tr><td>$5$</td><td rowspan="2">$\le 500$</td><td rowspan="2">$\le 3000$</td><td>保证图是一张有向无环图</td><td>$15$</td></tr><tr><td>$6$</td><td>无</td><td>$15$</td></tr></tbody></table></div>

<p>对于所有测试数据，满足 $1 \le n \le 500,0 \le m \le 3000$。</p>
<p>保证图中不存在自环，但是可能会存在重边。</p>
<p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=552">样例数据下载</a></p>
