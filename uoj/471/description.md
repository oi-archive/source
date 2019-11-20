# 题目描述

<p>九条可怜是一个喜欢出题的女孩子，这道题是一道有关浙江省选的硬核模拟题。</p>
<p>在 $9102$ 年，有 $n$ 名选手参加了浙江省选，其中第 $i$ 个选手的智力是 $a_i$，训练量是 $b_i$。作为出题人，可怜可以自由选择这套题的风格是比较偏套路还是比较偏智力。举例来说，ZJOI2018的题就比较偏智力，今年的题就比较偏套路。</p>
<p>为了定量衡量一套题的风格，可怜定义了反向选拔指数 $x$，$x$ 是一个<strong>非负整数</strong>。第 $i$ 个选手在反向选拔指数为 $x$ 的题目上的表现为 $a_ix+b_i$。在 $x$ 给定的情况下，第 $i$ 个人的排名为表现严格大于 $a_ix+b_i$ 的人数再加一。</p>
<p>在 $9102$ 年浙江省队的人数为 $m$，因此只有排名小于等于 $m$ 的人才能够进入浙江省队。注意当有并列的情况时，进入浙江省队的人数可能多于 $m$。</p>
<p>不难发现，选手的排名和 $x$ 的关系非常大。现在，可怜想让你计算，第$i$ 个选手有没有可能进入浙江省队，如果有可能，他最好的排名是多少。</p>

# 输入格式


<p>第一行输入两个整数 $n,m(m \leq n)$，表示选手总数以及浙江省队的人数。</p>
<p>接下来 $n$ 行每行两个整数 $a_i,b_i$，表示每个选手的属性值。</p>

# 输出格式


<p>输出一行 $n$ 个整数，如果第 $i$ 个选手进不了浙江省队，就输出 $-1$，否则输出他可能的最好排名。</p>

# 样例一


<h4>input</h4>
<pre><code>3 1
1 5
5 1
2 2</code></pre>
<h4>output</h4>
<pre><code>1 1 -1</code></pre>
<h4>explanation</h4>
<p>当 $x = 1$ 时，三个人的表现分别为 $6,6,4$，这时前两个人并列第一名，都能进入省队，而第三个人排名第三，没法进入省队。</p>
<p>当 $x&gt;1$ 时，第二个人的表现严格好于第三个人，而当 $x=0$ 时，第一个人的表现严格好于第三个人，因此第三个人无论 $x$ 怎么取，他都没有办法进入省队。</p>

# 样例二


<p>见样例数据下载</p>

# 限制与约定


<p>对于 $100\%$ 的数据，$1 \leq a_i\leq 10^9, 1 \leq b_i \leq 10^{18}$，$1 \leq m \leq n$。</p>
<p>对于 $100\%$ 的数据，保证选手的属性两两不同，即 $\forall 1 \leq i &lt; j\leq n$，有 $a_i \neq a_j$ 或 $b_i \neq b_j$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点</th>
    <th>$n$</th>
    <th>$m$</th>
  </tr></thead><tbody><tr><td>1</td>
    <td rowspan="2">$\leq 200$</td>
    <td rowspan="2">$\leq 20$</td>
  </tr><tr><td>2</td>
  </tr><tr><td>3</td>
    <td rowspan="3">$\leq 10^5$</td>
    <td>$=1$</td>
  </tr><tr><td>4</td>
    <td rowspan="2">$\leq 2$</td>
  </tr><tr><td>5</td>
  </tr><tr><td>6</td>
    <td rowspan="2">$\leq 2000$</td>
    <td rowspan="5">$\leq 20$</td>
  </tr><tr><td>7</td>
  </tr><tr><td>8</td>
    <td rowspan="3">$\leq 10^5$</td>
  </tr><tr><td>9</td>
  </tr><tr><td>10</td>
  </tr></tbody></table></div>

<p><strong>时间限制</strong>：$5\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=471">样例数据下载</a></p>
