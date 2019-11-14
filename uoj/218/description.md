# 题目描述

<p>uoj 旗下有一个火车站，用来管理属于 uoj 的小火车。</p>
<p>火车站一共有 $n$ 条编号为 $1, \dots, n$ 的，只有一端的用来存放小火车的铁路，由于小火车特殊的构造，每条铁路可以停放无数辆小火车。每条铁路是相互独立的。</p>
<p>铁路是一个栈结构，后停放的小火车可以先出来。</p>
<p>每辆小火车有一个吨位 $t$。</p>
<p>由于 NOI2016 即将到来，想要跟小火车正面作战的人多了起来，火车站管理员九条可怜每天需要处理很多事件。</p>
<p>事件可以概括成一下三种：</p>
<ul><li><code>1 l r</code> 有人想跟铁路编号在 $[l,r]$ 的每条铁路的<strong>第一辆可以开出来的小火车</strong>正面战斗，你需要统计这些小火车的吨位之和，没有火车的铁路不计入答案。</li>
<li><code>2 l</code> 编号为 $l$ 的铁路开走一辆火车，如果这条铁路没有小火车则不开出。</li>
<li><code>3 l r x</code> 铁路编号在 $[l,r]$ 的每条铁路都新停放一辆吨位为 $x$ 的火车。</li>
</ul><p>现在管理员九条可怜要去南海前线了，你需要替他管理火车站。</p>
<p>由于火车站很忙，所以你需要实时反馈信息，我们会用一些手段要求你强制在线，具体请看输入格式。</p>

# 输入格式


<p>输入第一行三个非负整数 $n,m,\mathrm{ty}$ 表示铁路的数量和操作次数还有是否强制在线。</p>
<p>接下来 $m$ 行，每行四个数或者三个数或者两个数表示一次操作。</p>
<p>为了实时反馈信息，你需要解密 $l,r$，设读入的是 $l_1,r_1$，则实际的值如下：</p>
<p>\begin{eqnarray}
l_2 &amp; = &amp; (l_1+\mathrm{lastans} \cdot \mathrm{ty}) \bmod n + 1 \\
r_2 &amp; = &amp; (r_1+\mathrm{lastans} \cdot \mathrm{ty}) \bmod n + 1 \\
l   &amp; = &amp; \min(l_2,r_2) \\
r   &amp; = &amp; \max(l_2,r_2)
\end{eqnarray}</p>
<p>$\mathrm{lastans}$ 表示上一次询问的答案，如果之前没有询问则为 $0$。</p>
<p>当你进行的是第二类操作时，只需要令 $l=(l_1+\mathrm{lastans} \cdot \mathrm{ty}) \bmod n+1$ 即可。</p>
<p>输入数据保证 $1\leq l_1,r_1\leq n$。</p>
<p><strong>注意，我们并没有加密吨位和操作类型</strong></p>

# 输出格式


<p>对于每个询问输出一行，一个非负整数表示答案。</p>

# 样例一


<h4>input</h4>
<pre>10 10 0
3 1 5 3
1 1 6
3 1 7 1
1 1 9
1 1 6
3 1 5 2
1 3 6
1 3 9
3 1 7 6
2 1


</pre>

<h4>output</h4>
<pre>15
7
6
7
8

</pre>


# 样例二


<h4>input</h4>
<pre>10 10 1
1 1 8
2 1
1 1 6
3 3 7 5
2 9
1 5 9
1 2 7
2 9
3 1 6 2
2 9


</pre>

<h4>output</h4>
<pre>0
0
15
25


</pre>


# 样例三


<p>见样例数据下载，限制与约定跟第 $6$ 个测试点相同。</p>

# 样例四


<p>见样例数据下载，限制与约定跟第 $10$ 个测试点相同。</p>

# 限制与约定


<div class="table-responsive">
    <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n,m$</th><th>$\mathrm{ty}$</th></tr></thead><tbody><tr><td>1</td><td rowspan="3">$\leq 10^3$</td><td rowspan="3">$=1$</td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td>$\leq 10^5$</td><td rowspan="3">$=0$</td></tr><tr><td>5</td><td>$\leq 2 \times 10^5$</td></tr><tr><td>6</td><td>$\leq 5 \times 10^5$</td></tr><tr><td>7</td><td>$\leq 10^5$</td><td rowspan="4">$=1$</td></tr><tr><td>8</td><td>$\leq 2 \times 10^5$</td></tr><tr><td>9</td><td>$\leq 3 \times 10^5$</td></tr><tr><td>10</td><td>$\leq 5 \times 10^5$</td></tr></tbody></table></div>

<p>对于所有数据，$1 \leq t \leq 10^3$。</p>
<p><strong>时间限制：</strong>$4\texttt{s}$</p>
<p><strong>空间限制：</strong>$1024\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=218">样例数据下载</a></p>
