# 题目描述

<p>小R购买了 $n$ 个不同厂家生产的灯泡。这些灯泡的寿命是一个随机变量。第 $i$ 个灯泡的一保质期为 $T_i$，在保质期内灯泡不会损坏。超出保质期后，灯泡的寿命服从参数为 $\lambda_i$ 的指数分布。形式化地说，设 $f_i (t)$ 表示第 $i$ 个灯泡寿命大于 $t$ 的概率，那么</p>
<p>$$f_i(t)=
\begin{cases}
1&amp;t \le T_i\\
e^{-\lambda_i(t-T_i)}&amp;t &gt; T_i
\end{cases}$$</p>
<p>其中，$1 \leq \lambda_i \leq 5$，且 $\lambda_i$ 是整数，$0\leq T_i &lt; 1$。</p>
<p>小R对灯泡寿命的排名做出了若干个预测，每个预测互不相干，预测了灯泡$i$的寿命在全部灯泡中排名第$j$（从大到小排名，从$1$开始计数）。</p>
<p>请你计算出每个预测准确的概率。</p>

# 输入格式


<p>第一行一个整数 $n$，表示灯泡的个数。</p>
<p>接下来 $n$ 行每行两个实数 $T_i$ 和 $\lambda_i$，表示第 $i$ 个灯泡的技术参数。</p>
<p>接下来一行一个整数 $m$，表示预测的个数。</p>
<p>接下来 $m$ 行，每行两个整数 $i, j$ 表示一个预测。</p>

# 输出格式


<p>对于每个预测，输出一行一个实数，表示这个预测正确的概率。
你的答案被认为是正确的当且仅当你的输出与标准输出的相对或绝对误差小于或等于 1e-6</p>

# 样例一


<h4>input</h4>
<pre>5
0.514 1
0.530 1
0.996 4
0.605 5
0.532 1
10
4 2
1 2
1 3
4 1
3 3
2 3
2 5
1 3
2 4
3 4

</pre>

<h4>output</h4>
<pre>0.040098
0.203478
0.169303
0.010344
0.356894
0.172687
0.163215
0.169303
0.170862
0.153489

</pre>


# 样例二


<h4>input</h4>
<pre>3
0.899 1
0.905 1
0.616 1
5
2 3
1 1
2 3
1 3
3 3

</pre>

<h4>output</h4>
<pre>0.248177
0.372920
0.248177
0.252671
0.499152

</pre>


# 样例三


<p>见样例数据下载。</p>

# 数据规模和约定


<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>$n$ 的规模</th>
<th>$m$ 的规模</th>
<th>其它约定</th>
</tr></thead><tbody><tr><td>1</td><td>$n \le 3$</td><td>$m \le 5$</td><td>无</td>
</tr><tr><td>2~3</td><td>$n \le 5$</td><td>$m \le 10$</td><td>无</td>
</tr><tr><td>4~5</td><td>$n \le 30$</td><td>$m \le 300$</td><td>无</td>
</tr><tr><td>6~7</td><td>$n \le 10$</td><td>$m \le 50$</td><td>$\lambda_i = 1$</td>
</tr><tr><td>8~10</td><td>$n \le 50$</td><td>$m \le 300$</td><td>无</td>
</tr></tbody></table></div>


# 注意事项


<p>这道题在某些极端数据下可能会出现严重的精度误差，但是这题的数据都是随机的，因此可以忽略那些极端情况。</p>
<p>因为数据是随机的，所以此题不开放 hack 功能。</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=162">样例数据下载</a></p>
