# 题目描述

<p>妹滋滋是一个善于编程的女孩子。</p>
<p>但是某一天，她一不小心把 UOJ 后台的票数统计程序写错了。</p>
<p>本来嘛在这种根本没有什么用的功能上出了 bug 也没有什么大关系，但是又有某一天，UOJ 突然就开始搞全民公投了。</p>
<p>这可怎么办呢？如果这个消息让别人知道的话自己肯定会被查表，更不要说让所有用户重新来投一次票了。</p>
<p>作为一个要强的女孩子，妹滋滋决定自力更生。</p>
<p>通过一些奥妙重重的方式，妹滋滋知道了一些关于这次全民公投的信息。</p>
<ol><li>这次全民公投一共有 $n$ 位用户排队参加，编号为 $1$ 到 $n$。每一位用户要么投了通过，要么投了不通过。</li>
<li>有 $m$ 个二元组 $(x_i,y_i)$，每个二元组给出这样一个信息： “前 $x_i$ 位用户中，恰好 $y_i$ 位投了通过” 和 “后 $y_i$ 位用户中，恰好有 $x_i$ 位投了通过” 这两句话中，至少有一句是成立的。</li>
</ol><p>作为分析的第一步，她想要知道有多少种投票情况是满足她所得到的信息的。当然，可能所有投票情况都不满足条件。</p>

# 输入格式


<p>输入第一行一个正整数 $T$ 表示数据组数。</p>
<p>对于每组数据，第一行有两个空格隔开的正整数 $n,m$。</p>
<p>接下来 $m$ 行每行两个空格隔开的正整数 $x_i,y_i$，保证 $0 \leq x_i,y_i \leq n$ 且 $x_i,y_i$ 不全为 $0$。</p>

# 输出格式


<p>对于每组数据输出一行表示答案，答案可能很大，只需要输出对 $998244353$（$7 \times 17 \times 2^{23} + 1$，一个质数） 取模后的值。</p>

# 样例一


<h4>input</h4>
<pre>2
3 1
2 1
5 3
1 3
4 2
3 1

</pre>

<h4>output</h4>
<pre>4
2

</pre>


# explanation


<p>用 $0$ 表示不通过，$1$ 表示通过。</p>
<p>满足第一组数据的情况有：$(100),(101),(010),(011)$。</p>
<p>满足第二组数据的情况有：$(10010),(01010)$。</p>

# 样例二


<p>见样例数据下载。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$</th>
<th>$m$</th>
<th>约定</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="5">$n \leq 20$</td><td rowspan="3">$m \leq 20$</td><td rowspan="5"></td></tr><tr><td>2</td></tr><tr><td>3</td></tr><tr><td>4</td><td rowspan="3">$m \leq 1000$</td></tr><tr><td>5</td></tr><tr><td>6</td><td rowspan="1">$n \leq 5000$</td><td rowspan="1">保证 $x_i \lt y_i$</td></tr><tr><td>7</td><td rowspan="2">$n \leq 60$</td><td rowspan="2">$m \leq 60$</td><td rowspan="4"></td></tr><tr><td>8</td></tr><tr><td>9</td><td rowspan="2">$n \leq 5000$</td><td rowspan="2">$m \leq 1000$</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有数据，$T \leq 5$。</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=209">样例数据下载</a></p>
