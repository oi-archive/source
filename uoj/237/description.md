# 题目描述

<p>Pavel 有一个非常简单的铁路玩具。 它有一条含有 $n$ 个车站的主干线并且连续编号为 $0$ 到 $n−1$。车站 $0$ 和车站 $n−1$ 就在这条主干线的两端。其中车站 $i$ 和车站 $i+1$ 之间的距离为 $l_i$ 厘米（$0\le i &lt; n - 1$）。</p>
<p>除了这条主干线之外，这个铁路也许会有些支线。每条支线都是由主干线中的一个车站和主干线 外的一个新车站之间的一条新铁路构成（这些新的车站不会被编号）。在主干线中的一个车站最多只能有一条支线。以主干线中的车站 $i$ 为起点的支线的长度为 $d_i$ 厘米。我们用 $d_i = 0$ 来表示车站 $i$ 没有支线。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/237/sample1.png" alt="图1" style="width:500px;"/></p>
<p>Pavel 现正规划一条快捷方式：一条在主干线中两个不相同的车站之间（它们可能相邻）的快速干线。这条快速干线无论是连接哪两个车站，它的长度都将会恰好是 $c$ 厘米。</p>
<p>铁路中的每一段，包括那条新的快速干线，都能够双向行驶。任意两个车站的距离就是它们之间沿着铁路由一个车站到另一个车站之间最短路径的长度。所有车站组合中最大的距离就叫做整个铁路网络的直径。换句话说，存在一个最小值 $t$ 使任意两个车站之间的距离都不会超过 $t$。</p>
<p>Pavel 就是想建造一条快速干线，使得有了这条快速干线后新的铁路网络的直径能达到最小值。</p>

# 实现细节


<p>你应该实现以下函数（方法）：</p>
<ul><li><code>long long find_shortcut(int n, std::vector&lt;int&gt; l, std::vector&lt;int&gt; d, int c)</code><ul><li><code>n</code>：主干线中的车站数目，</li>
<li><code>l</code>：主干线中车站之间的距离（数组的长度为 $n - 1$），</li>
<li><code>d</code>：支线的长度（数组的长度为 $n$），</li>
<li><code>c</code>：新快速干线的长度。</li>
<li>函数应该返回加入新快速干线后铁路网络直径的最小可能值。</li>
</ul></li>
</ul><p>请使用提供的模板文件，参考关于你所使用的编程语言的实现细节。</p>

# 样例一


<p>对于上图所示的铁路网络，样例评分程序会调用以下函数：</p>
<p><code>find_shortcut(4, [10, 20, 20], [0, 40, 0, 30], 10)</code></p>
<p>最优解是在车站 1 和车站 3 之间建造一条快速干线，如下图所示。</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/237/sample2.png" alt="图2" style="width:500px;"/></p>
<p>这个新铁路网络的直径是 $80$ 厘米，所以函数应该返回数值 $80$。</p>

# 样例二


<p>样例评分程序会调用以下函数：</p>
<p><code>find_shortcut(9, [10, 10, 10, 10, 10, 10, 10, 10], [20, 0, 30, 0, 0, 40, 0, 40, 0], 30)</code></p>
<p>最优解是连接车站 2 和车站 7，这个解的直径是 $110$。</p>

# 样例三


<p>样例评分程序会调用以下函数：</p>
<p><code>find_shortcut(4, [2, 2, 2], [1, 10, 10, 1], 1)</code></p>
<p>最优解是连接车站 1 和车站 2，这样直径将被缩短到 $21$。</p>

# 样例四


<p>样例评分程序会调用以下函数：</p>
<p><code>find_shortcut(3, [1, 1], [1, 1, 1], 3)</code></p>
<p>在任意两个车站中建立长度为 $3$ 的快速干线都不会改进整个铁路网络的直径，因此其直径仍为初始值 $4$。</p>

# 子任务


<p>在所有子任务中 $2 \le n \le 10^6, 1 \le l_i \le 10^9, 0 \le d_i \le 10^9, 1 \le c \le 10^9$。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
<th>分数</th>
<th>$n \le $</th>
</tr></thead><tbody><tr><td>1</td><td>9</td><td>$10$</td></tr><tr><td>2</td><td>14</td><td>$100$</td></tr><tr><td>3</td><td>8</td><td>$250$</td></tr><tr><td>4</td><td>7</td><td>$500$</td></tr><tr><td>5</td><td>33</td><td>$3000$</td></tr><tr><td>6</td><td>22</td><td>$100000$</td></tr><tr><td>7</td><td>4</td><td>$300000$</td></tr><tr><td>8</td><td>3</td><td>$1000000$</td></tr></tbody></table></div>



# 评测方式


<p>评测程序将会按照下列格式读取输入数据：</p>
<ul><li>第一行：两个整数 $n$ 和 $c$，</li>
<li>第二行：整数 $l_0, l_1, \ldots, l_{n - 2}$，</li>
<li>第三行：整数 $d_0, d_1, \ldots, d_{n - 1}$。</li>
</ul><p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$2\texttt{GB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=237">样例及测评库下载</a></p>
