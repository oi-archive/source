# 题目描述

<p><strong>这是一道交互题</strong></p>
<p>跳蚤们已经修好了$m$条道路连通了$n(n \ge 2)$只Dog（这些道路中无重边无自环）。但是它们马上发现了一个很大的问题，$n$只Dog中并不全是SingleDog，也有一些是DoubleDog。</p>
<p>Dog们给了跳蚤们一个提示：这$m$条道路中，每一条都连接的是一只SingleDog和一只DoubleDog。不存在一条道路连接两只SingleDog或者两只DoubleDog。即图是一张二分图。</p>
<p>现在跳蚤们需要你把这些Dog给划分出来。跳蚤们不直接告诉你这$m$条道路，而是给了你这样一个功能：你可以进行若干次询问。每次询问你告诉跳蚤们一些点对，这些点对对应一个道路的集合，跳蚤们将回答如果将$m$条道路中在这个集合的道路去掉之后这$n$只Dog是否仍然连通。注意道路 $ (x, y) $ 和 $ (y, x) $ 是等价的，一次询问中一条道路加入多次和加入一次的效果相同。</p>
<p>你需要在<strong>2000次询问内</strong>内找出所有的SingleDog或者DoubleDog（即输出二分图的一侧），或判断跳蚤们的提示是错误的（图不是二分图），<strong>在这个情况下返回空集</strong>。可以证明因为图连通且点数至少为2，二分图的一部分不可能是空集。</p>

# 任务


<p>你需要实现下面的过程：</p>
<pre><code class="sh_cpp">std::vector&lt;int&gt; check_bipartite(int vsize);</code></pre>
<p>其中 <code>vsize</code> 是Dog的数量，也就是题目描述中的 $ n $。</p>
<p>你可以调用以下过程和交互库进行交互：</p>
<pre><code class="sh_cpp">bool query(std::vector&lt;std::pair&lt;int, int&gt;&gt; banned_edges);</code></pre>
<p>其中 <code>banned_edges</code> 是一个包含点对的 vector，表示你要去掉的点对。当图仍然联通时返回值为<code>true</code>，否则为<code>false</code>。你必须保证所有点对合法，否则你将的得到 0 分。所谓点对合法就是值点对中的<strong>每个编号都必须合法，且两个点不能相同</strong>。</p>

# 评测方式


<p>评测程序示例将读入如下格式的输入数据：</p>
<p>第一行包括两个正整数 $ n $ 和 $ m $；</p>
<p>接下来 $ m $ 行，每行表示一条边的两个端点。</p>
<p><strong>请注意点的编号从0开始</strong>。</p>
<p>评测程序示例将输出如下格式的输出数据：</p>
<p>第一行一个非负整数，表示二分图一部分的点数，如果是0表示不是二分图。</p>
<p>接下来一行空格隔开的数表示二分图一侧的每个点。</p>
<p><strong>请注意点的编号从0开始</strong>。</p>

# 样例一至样例四


<p>见样例及交互库下载</p>

# 限制与约定


<p>对于所有数据，保证 $n - 1 \le m \le \frac{n (n - 1)}{2}$，且 $ 2 \le n \le 200 $。</p>
<p><strong>Subtask 1 (13 分):</strong> $n\le 10$，保证图是二分图。</p>
<p><strong>Subtask 2 (24 分):</strong> $n\le 40$，保证图是二分图。</p>
<p><strong>Subtask 3 (30 分):</strong> $n\le 100$</p>
<p><strong>Subtask 4 (33 分):</strong> $n\le 200$</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p>在本题中，本地测试时可以将 <code>graderlib.cpp</code> 和 <code>grader.cpp</code> 一起粘到提交程序之前。</p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=461">样例及交互库下载</a></p>
