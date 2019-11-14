# 题目描述

<p>通过一些不可描述的方式，妹滋滋算出了 $51\%$ 的得票率，于是就她就把这个公开给了广大用户 —— UOJ 解散已成定局。</p>
<p>几个小时后，UOJ 创始人伏特跳蚤国王宣布辞职，即日起退出 UOJ 团队。</p>
<p>这两个消息在算法竞赛界引起了轩然大波，“UOJ 是什么”“废除UOJ有什么影响” 马上成为了网民们的搜索热点并出现在了各大搜索网站的首页上。</p>
<p>著名的大水群和三连击发源地 —— Universal OJ 用户群随之解散，导致大量 OI 水狗们无处可水。一段时间后，圈子里渐渐传出了恢复 UOJ 的呼声，更有一些人将这个烂摊子归咎于那些投票通过的用户 —— 他们决定找出这些人并加以指责。</p>
<p>经过一段时间的搜索，他们找到了 $n$ 个嫌疑人，编号为 $1$ 到 $n$，导致 UOJ 解散的犯人就在他们之间。严刑拷打之下，他们交代了一些供词，供词有两类：</p>
<ol><li>$x_i$ 说 $y_i$ 是犯人。</li>
<li>$x_i$ 说 $y_i$ 不是犯人。</li>
</ol><p>然而，让事情变得复杂的是，犯人们并不打算背锅，所以<strong>他们的供词不总是真的</strong>，同时，为了不闹乌龙暴露自己，<strong>每一个犯人的所有供词最多有一句是假的，而不是犯人的嫌疑人的供词总是真的。</strong></p>
<p>现在给出了全部的 $m$ 条供词，你需要找出哪些人是犯人。如果有多解，输出任何一组解即可。</p>

# 输入格式


<p>第一行两个正整数 $n, m$，表示犯人数目与供词数目。</p>
<p>接下来 $m$ 行，每行三个整数 $x_i,y_i,t_i$。其中 $t_i = 0$ 表示 $x_i$ 说 $y_i$ 是犯人，$t_i = 1$ 表示 $x_i$ 说 $y_i$ 不是犯人。</p>

# 输出格式


<p>第一行一个整数 $c$ 表示犯人的数目。</p>
<p>第二行 $c$ 个整数 $p_i$，按照升序输出所有犯人的编号。</p>
<p>如果不存在一个犯人的集合使得供词满足条件，输出一行一个单词 &#34;<samp>Impossible</samp>&#34;。</p>

# 样例一


<h4>input</h4>
<pre>2 2
1 2 0
2 1 0

</pre>

<h4>output</h4>
<pre>2
1 2

</pre>

<h4>explanation</h4>
<p>容易看出除了没有犯人的情况，其他三种情况都是满足条件的。</p>

# 样例二


<h4>input</h4>
<pre>3 4
1 1 1
2 2 1
1 3 1
2 3 0

</pre>

<h4>output</h4>
<pre>Impossible

</pre>

<h4>explanation</h4>
<p>不论如何，第 $3,4$ 条证言都一定是真的，而这两条证言互相矛盾。</p>

# 样例三


<p>见样例数据下载。</p>

# 限制与约定


<p>由于一些原因，本题使用捆绑测试。每个子任务有若干个测试点，分为 $5$ 个子任务，你只有通过一个子任务的所有测试点才能得到这个子任务的分数。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分值</th>
<th>$n$的规模</th>
<th>$m$的规模</th>
<th>其他限制</th>
</tr></thead><tbody><tr><td>1</td><td>10</td><td>$10$</td><td>$10$</td><td>无</td></tr><tr><td>2</td><td>15</td><td>$5 \times 10^4$</td><td>$10^5$</td><td>每个嫌疑人最多说 $2$ 条供词</td></tr><tr><td>3</td><td>15</td><td>$10^4$</td><td>$10^5$</td><td>每个嫌疑人最多说 $10$ 条供词</td></tr><tr><td>4</td><td>20</td><td>$300$</td><td>$10^5$</td><td>$m=n(n-1)$ 且对于所有 $1 \leq p,q \leq n$且$p \neq q$ 的 $p,q$，$x_i=p,y_i=q$ 恰好出现一次</td></tr><tr><td>5</td><td>40</td><td>$10^5$</td><td>$10^5$</td><td>无</td></tr></tbody></table></div>

<p>对于所有数据，$1 \leq n,m \leq 10^5$，$1 \leq x_i,y_i \leq n$，$t_i \in \{0,1\}$</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=210">样例数据下载</a></p>
