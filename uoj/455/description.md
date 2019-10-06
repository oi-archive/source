# 题目描述

<p>由于输了比赛，小 $C$ 需要请客。但是现在外面已经是大雪连天了，所以小C决定叫外卖。</p>
<p>受到雪灾的影响，很多餐厅没有采购到足够的食材，因此小C不得不从不同的餐厅购买食物，更加悲催的是因为雪灾的原因，送餐员最多只能携带一道菜，且最多只送一次。</p>
<p>现在小 $C$ 需要叫 $n$ 道菜，于是他联系了 $n$ 名送餐员。</p>
<p>送餐员和餐厅可以看成在一条直线上。第 $i$ 名送餐员有一个整数坐标 $x_i$，且他索要的工资为$|\text{他所在的坐标}-\text{餐厅的坐标}|$元。
第 $j$ 家餐厅有一个整数坐标 $y_j$，且它们的食材只能提供不超过 $c_j$ 道菜，每道菜价值 $w_j$ 元。</p>
<p>现在小 $C$ 希望知道，他的最小花费。</p>

# 输入格式


<p>第一行两个整数 $n,m$，表示送餐员的数量和餐厅的数量。</p>
<p>接下来一行 $n$ 个整数表示 $x_1 \ldots x_n$，保证 $ x_i \le x_{i + 1} $ 。</p>
<p>接下来 $m$ 行，第 $i$ 行包括三个整数 $y_i,w_i,c_i$，保证 $ y_i \le y_{i + 1} $ 。</p>

# 输出格式


<p>输出一个整数表示答案，无解输出 -1.</p>

# 样例一


<h4>input</h4>
<pre>4 4
8 8 9 10
1 4 1
3 0 1
5 0 1
10 2 1

</pre>

<h4>output</h4>
<pre>22

</pre>

<h4>explanation</h4>
<p>小 $ C $ 的最优方案为：第一个送餐员去第一个餐厅，第二个送餐员去第二个餐厅，第三个送餐员去第三个餐厅，第四个送餐员去第四个餐厅。这种方案的总花费为 $ 22 $。</p>

# 样例二至样例七


<p>见样例数据下载</p>

# 限制与约定


<p>对于100%的数据，有 $2 \le n,m \le 10^5, 0 \le x_i, y_i, c_i, w_i \le 10^9$。</p>
<p><strong>Subtask 1(5 分)</strong>:  $n,m \le 5​$</p>
<p><strong>Subtask 2(20 分)</strong>: $n \le 300,m \le 1000$</p>
<p><strong>Subtask 3(25 分)</strong>: $n,m \le 5000$</p>
<p><strong>Subtask 4(9 分)</strong>: $\forall i \in [1,m],w_i=0,\sum_{i=1}^{m}c_i \le 10^6$</p>
<p><strong>Subtask 5(11 分)</strong>: $\sum_{i=1}^{m}c_i \le 10^6$</p>
<p><strong>Subtask 6(11 分)</strong>: $\forall i \in [1,m],w_i=0$</p>
<p><strong>Subtask 7(19 分)</strong>: 无其他限制</p>
<p><strong>时间限制</strong>：$\texttt{1s}$</p>
<p><strong>空间限制</strong>：$\texttt{256MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=455">样例数据下载</a></p>
