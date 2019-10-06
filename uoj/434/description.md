# 题目描述

<p>按照剧本，<strong>f<font color="#FF0000">ateicest</font></strong> 想要去买东西。而他自然要前往鸽巢去买东西。</p>
<p>鸽巢的商城是一个 $H \times W​$ 的网格，西北角标号为 $(1,1)​$，东南角标号为 $(H,W)​$，从北向南标号为 $1 \dots H​$，从西向东标号为 $1 \dots W​$。每个格子中都有一个商店，每家商店都会卖一样商品，不同的商店卖的商品互不相同。这个商城中划分出了 $n+2​$ 个区域，作为功能区，我们将其标号为 $0 \dots n+1​$。每个区域是一个矩形，第 $i​$ 个矩形以 $(x_{l_i},y_{l_i})​$ 为左上角，$(x_{r_i},y_{r_i})​$ 为右下角。这 $n+1​$ 个矩形满足下列条件：</p>
<p>$$x_{l_0} \le x_{r_0} &lt; x_{l_1} \le x_{r_1} &lt; \dots &lt; x_{l_{n+1}} \le x_{r_{n+1}}​$$</p>
<p>$$y_{l_0} \le y_{r_0} &lt; y_{l_1} \le y_{r_1} &lt; \dots &lt; y_{l_{n+1}} \le y_{r_{n+1}}​$$</p>
<p>其中，第 $0$ 个区域中的每个格子有一个传送门，可以把 <strong>f<font color="#FF0000">ateicest</font></strong> 传入商场；第 $n+1$ 个区域中每个格子，可以把 <strong>f<font color="#FF0000">ateicest</font></strong> 传出商场；中间的第 $1$ 号到第 $n$ 号区域都是美食街，其中的每个格子都有一家餐馆。当然，这个商城的每个格子都很大，因此功能区并不影响格子里面有商店，即就算是功能区，格子里面依然是有商店的。注意到第 $0$ 号和第 $n+1$ 号区域里面是没有餐馆的。</p>
<p>由于 <strong>f<font color="#FF0000">ateicest</font></strong> 是个购物狂，因此他每经过一家商店，都会进去买一份那家商店的商品，包括起点和终点。如果他经过一家餐馆，他可以选择进去吃或是不进去吃。但是他非常想品尝这里的美食，因此他决定除 $0$ 号和 $n+1$ 号以外的每个区域至少进一家餐馆。</p>
<p><strong>f<font color="#FF0000">ateicest</font></strong> 可以任选从第 $0$ 号区域的哪个格子进入商城，从第 $n+1$ 号区域的哪个格子出去。他还可以任意选择走的路线。但因为他不想在这个商城花太多的时间，他只能向东或者向南走，即沿着一条最短路到出去的地方。</p>
<p><strong>f<font color="#FF0000">ateicest</font></strong> 想要知道，他在完成这次购物后，能有多少种不同的经历。两种经历是不同的当且仅当他买的东西集合不一样或者去的餐馆集合不一样。</p>
<p><strong>f<font color="#FF0000">ateicest</font></strong> 当然飞快地报出了答案，但是他想考考你。由于 <strong>f<font color="#FF0000">ateicest</font></strong> 认为你不能像他那样飞快地报出答案，他只要你报出答案对 $998244353$ 取模后的结果就行了。</p>

# 输入格式


<p>从标准输入读入数据。 </p>
<p>输入第一行两个整数 $H$，$W$，表示网格大小。</p>
<p>第二行一个整数 $n$，表示区域个数。</p>
<p>接下来 $n+2$ 行，即第 $3$ 行到第 $n+4$ 行，每行四个整数 $x_{l_i}$，$y_{l_i}$，$x_{r_i}$，$y_{r_i}$，表示一个区域的范围，第 $i$ 行表示第 $i-3$ 个区域。</p>

# 输出格式


<p>输出到标准输出中。 </p>
<p>输出一行一个整数，表示方案数对 $998244353$ 取模后的结果。</p>

# 样例一


<h4>input</h4>
<pre><code>1000 1000
2
1 1 1 1
3 3 3 3
5 5 5 5
7 7 7 7</code></pre>
<h4>output</h4>
<pre><code>216</code></pre>
<h4>explanation</h4>
<p>网格左上角长成这样：</p>
<pre><code>0......
.......
..1....
.......
....2..
.......
......3</code></pre>
<p>其中他只能从 $0$ 入，$3$ 出，并且 $1$ 和 $2$ 都必须经过。因此从 $0$ 到 $1$ 有 $6$ 种方案，从 $1$ 到 $2$ 也有 $6$ 种方案，从 $2$ 到 $3$ 也有六种方案。一共是 $6^3 = 216$ 种方案。</p>

# 样例二


<h4>input</h4>
<pre><code>1000 1000
0
1 1 2 2
4 4 5 5</code></pre>
<h4>output</h4>
<pre><code>366</code></pre>

# 样例三


<h4>input</h4>
<pre><code>50 50
1
1 1 10 12
20 17 25 32
30 42 47 45</code></pre>
<h4>output</h4>
<pre><code>545916062</code></pre>

# 限制与约定


<p>本题采用捆绑测试。</p>
<p>我们令
$$
AMX = \max_{0 \le i \le n+1} \{ \max \{ x_{r_i} - x_{l_i} + 1, y_{r_i} - y_{l_i} + 1 \} \} \\
$$</p>
<p>对于所有数据，满足：</p>
<ul><li>$2 \le H, W \le 2 \times 10^5$</li>
<li>$0 \le n \le \min \{ H, W \} - 2$</li>
<li>对于 $\forall$ $0 \le i \le n+1$，有 $1 \le x_{l_i} \le x_{r_i} \le H, 1 \le y_{l_i} \le y_{r_i} \le W$</li>
<li>对于 $\forall$ $0 \le i \le n$，有 $x_{r_i} &lt; x_{l_{i+1}}, y_{r_i} &lt; y_{l_{i+1}}$</li>
</ul><p>共有 $9$ 个子任务，每个子任务的特殊限制和分值如下：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-verticle-middle"><thead><tr><th>子任务编号</th>
    <th>分值</th>
    <th>$H, W$</th>
    <th>$n$</th>
    <th>$AMX$</th>
  </tr></thead><tbody><tr><td>1</td>
    <td>2</td>
    <td>$\le 4$</td>
    <td>——</td>
    <td>——</td>
  </tr><tr><td>2</td>
    <td>5</td>
    <td>$\le 300$</td>
    <td>$\le 300$</td>
    <td>——</td>
  </tr><tr><td>3</td>
    <td>11</td>
    <td>$\le 2 \times 10^3$</td>
    <td>——</td>
    <td>——</td>
  </tr><tr><td>4</td>
    <td>4</td>
    <td>——</td>
    <td>——</td>
    <td>$= 1$</td>
  </tr><tr><td>5</td>
    <td>8</td>
    <td>——</td>
    <td>$= 0$</td>
    <td>$\le 10^3$</td>
  </tr><tr><td>6</td>
    <td>15</td>
    <td>——</td>
    <td>$= 0$</td>
    <td>——</td>
  </tr><tr><td>7</td>
    <td>9</td>
    <td>——</td>
    <td>$= 1$</td>
    <td>$\le 10^3$</td>
  </tr><tr><td>8</td>
    <td>21</td>
    <td>——</td>
    <td>$= 1$</td>
    <td>——</td>
  </tr><tr><td>9</td>
    <td>25</td>
    <td>——</td>
    <td>——</td>
    <td>——</td>
  </tr></tbody></table></div>

<p><strong>时间限制</strong>：$\texttt{2s}$</p>
<p><strong>空间限制</strong>：$\texttt{512MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=434">样例数据下载</a></p>
