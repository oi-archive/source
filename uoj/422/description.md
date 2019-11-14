# 题目描述

<p>小Z有一个神奇的自动售货机，里面有 $n \times m$ 种物品，分别放在 $n$ 行 $m$ 列个格子中。每当小Z向自动售货机中投入一枚硬币，他就能获得一对相邻格子中的物品（已经获得的物品可能再次获得），获得每一对相邻格子中的物品的概率是相等的。在这 $n \times m$ 种物品中，有一些物品是小Z喜欢的（小Z喜欢的用 * [星号] 表示，其他的用 .[英文句号] 表示），他想把这些物品包装成一份礼物。小Z想知道，期望投入多少枚硬币后，就可以获得这些他喜欢的物品。</p>

# 输入格式


<p>第一行两个整数 $n$ 和 $m$。</p>
<p>接下来 $n$ 行，每行一个长度为 $m$ 的字符串，字符串中仅包含 * 和 . 两种字符。</p>

# 输出格式


<p>一个整数，表示在模 $998244353$ 意义下的答案。</p>

# 样例一


<h4>input</h4>
<pre><code>1 3
***</code></pre>
<h4>output</h4>
<pre><code>3</code></pre>

# 样例二


<h4>input</h4>
<pre><code>3 3
..*
*.*
.*.</code></pre>
<h4>output</h4>
<pre><code>404051295</code></pre>

# 限制和约定


<p>对于所有数据，保证 $1 \leq n \leq 6, 2 \leq m \leq 100$。</p>
<p>本题使用捆绑测试。每个子任务有若干个测试点，分为 $5$ 个子任务，你只有通过一个子任务的所有测试点才能得到这个子任务的分数。</p>
<p>为方便表示，设 $cnt$ 为输入中 * 的数量， $s$ 为由 * 组成的最大连通块(四连通)的大小。</p>
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th><th>分值</th><th>限制</th></tr></thead><tbody><tr><td>1</td><td>10</td><td>$cnt \leq 6$</td></tr><tr><td>2</td><td>20</td><td>$cnt \leq 20$</td></tr><tr><td>3</td><td>20</td><td>$s \leq 1$</td></tr><tr><td>4</td><td>20</td><td>$s \leq 16$</td></tr><tr><td>5</td><td>30</td><td>无特殊限制</td></tr></tbody></table><p><strong>时间限制</strong>：$1\texttt{s}$</p>
<p><strong>空间限制</strong>：$512\texttt{MB}$</p>
