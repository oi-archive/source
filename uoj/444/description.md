# 题目描述

<p><strong>这是一道交互题</strong></p>
<p>定义二分图为一种可以将点集$V$划分为$S$和$T$的图，满足条件：</p>
<ul><li>$1.S∪T=V，S∩T=Φ$</li>
<li>$2.对于所有(x,y)∈E，有x∈S，y∈T或x∈T，y∈S$</li>
</ul><p>你也可以选择<a href="//baike.baidu.com/item/%E4%BA%8C%E5%88%86%E5%9B%BE/9089095?fr=aladdin">百度</a>来帮助理解二分图的定义。</p>
<p>定义二分图的一个$k$划分方案为将二分图中每一条边染任意一种$1$到$k$之间的颜色的方案。</p>
<p>定义在二分图的一种$k$划分方案中$w_{ij}$表示经过第$i$个点的颜色为$j$的边的条数。</p>
<p>定义在二分图的一种$k$划分方案中节点$i$的不平均度为$max_{w_{ij}}-min_{w_{ij}},j∈[1,k]$。</p>
<p>定义二分图的一种$k​$划分方案中的不平均度为所有节点的不平均度之和。</p>

# 题目描述


<p>给定一个$S$,$T$中各有$n$个点的二分图。</p>
<p>其中点的编号为$1, \dots ,n$。</p>
<p>初始时候二分图内没有任何一条边,也就是$V=Φ$。</p>
<p>你需要动态支持向图中加边，删边。</p>
<p>同时求出任意一个不均匀度最小的$k$划分方案。</p>
<p>注意，在本题中$S$集合和$T$集合中的点<strong>不会随着图改变</strong>，也就是说,$S$集合和$T$集合在同一个问题(测试点)中是<strong>不变的</strong>。</p>

# 任务介绍


<p>你需要实现两个函数<code>Init</code>和<code>Modify</code>。</p>
<ul><li><p><code>Init(n,k,Q)</code></p>
<ul><li><code>n,k</code>含义见题目描述。</li>
<li><code>Q</code>为操作的个数。</li>
<li>你不需要返回任何值。</li>
</ul></li>
</ul><p>在每个测试点中，交互库都会调用恰好一次<code>Init</code>函数。</p>
<ul><li><p><code>Modify(x,y)</code></p>
<ul><li><code>x,y</code>是两个$1, \dots ,n$的数。</li>
<li>该函数改变连接$S$集合中第$x$个点到$T$集合中第$y$个点的边的存在性。</li>
<li>你需要返回在改变存在性之后的任意一种$k$划分方案。</li>
</ul></li>
</ul><p>在每个测试点中，交互库都会调用恰好$Q$次<code>Modify</code>函数。</p>
<p>由于检验时间<strong>非常大</strong>，实际测评时候SPJ仅仅会<strong>纯随机检测</strong>$min(Q,50000)$个方案的正确性。如果对于选出的min(Q,50000)个方案都最优则算AC。但是选手仍然需要<strong>返回所有操作之后的答案</strong>因为没有人可以确定这个方案是否会被检测。即使同一个程序的不同提交检测的也是<strong>不同的操作之后的方案</strong>。这个机制只会被用于<strong>加速测评</strong>，请不要使用这个机制骗取AC。</p>
<p>由于某些特殊原因，下发SPJ不支持随机检测。</p>

# 实现方法


<p>本题只支持<code>C++</code>。</p>
<p>源代码中需要包含头文件<code>graph.h</code>。</p>
<p>你需要实现的函数的相关接口:</p>
<pre><code class="sh_cpp">void Init(int n,int k,int Q);
Division Modify(int x,int y);</code></pre>
<p>其中<code>division</code>定义如下</p>
<pre><code class="sh_cpp">struct Division{int color[22][22];};</code></pre>
<p>其中$color_{ij}$表示$S$集合中的第$i$个节点到$T$集合中的第$j$个节点的边的颜色。</p>
<p>对于不存在那一条边，则该元素值<strong>必须为0</strong>.</p>

# 如何测试你的程序


<p>你需要在本题目录下使用如下命令编译得到可执行程序：</p>
<pre><code class="sh_bash">g++ -o graph grader.cpp graph.cpp -O2</code></pre>
<p>可执行文件将从<strong>标准输入</strong>读取以下格式的数据：</p>
<p>第一行包含一个正整数$seed$，需要保证$0 \leq seed \leq 2^{30}-1$。
* 为方便选手调试，在$seed$为零时数据不会进行加密。</p>
<p>第二行一共三个正整数，$n,k,Q$，需要保证$2 \leq k \leq n \leq 20 ,1 \leq Q \leq 500000$。</p>
<p>读入完成之后，交互库将会调用<code>Init</code>函数。</p>
<p>接下来$Q$行，一行两个整数$x,y$。需要保证$1 \leq x,y \leq n$</p>
<p>每一行读入完成之后，交互库会调用<code>Modify</code>函数</p>
<p>交互库将会在<strong>标准输出</strong>中输出以下信息：</p>
<p>每一次调用完<code>Modify</code>函数后，交互库都会输出一行形如<code>Count: cnt</code>的输出，其中cnt为你的方案的不平均度。
* 如果你给出的方案不合法的话cnt会等于 -1。</p>
<p><strong>注意</strong>最终测评时使用的$grader$和下发的$grader$<strong>不同</strong></p>

# 样例源代码


<p>在本题目录下，有C++语言的样例源代码graph.cpp。按照上文中提到的方式进行编译，即能通过编译得到可执行程序。</p>
<p>样例源代码只是帮助理解题目，结果<strong>一定不正确</strong>。</p>

# 限制与约定


<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th><th>$n\le$</th><th>$k\le$</th><th>$Q\le$</th></tr></thead><tbody><tr><td>$1$</td><td>$5$</td><td>$2$</td><td>$5$</td></tr><tr><td>$2$</td><td>$10$</td><td>$2$</td><td>$100$</td></tr><tr><td>$3$</td><td>$20$</td><td>$2$</td><td>$1000$</td></tr><tr><td>$4$</td><td>$20$</td><td>$2$</td><td>$10000$</td></tr><tr><td>$5$</td><td>$20$</td><td>$2$</td><td>$100000$</td></tr><tr><td>$6$</td><td>$20$</td><td>$10$</td><td>$1000$</td></tr><tr><td>$7$</td><td>$20$</td><td>$10$</td><td>$10000$</td></tr><tr><td>$8$</td><td>$20$</td><td>$10$</td><td>$100000$</td></tr><tr><td>$9$</td><td>$20$</td><td>$10$</td><td>$250000$</td></tr><tr><td>$10$</td><td>$20$</td><td>$10$</td><td>$500000$</td></tr></tbody></table></div>

<p>对于所有数据，满足$2 \leq n,k,1 \leq Q$</p>
<p><strong>时间限制</strong>：$\texttt{1s}$</p>
<p><strong>空间限制</strong>：$\texttt{512MB}$</p>
<p>题目中所给的时间、空间限制为你的代码和交互库加起来可以使用的时间和空间。我们保证，对于任何合法的数据，任何版本的交互库（包括下发给选手的和最终评测使用的），在检验次数<strong>不超过50000次</strong>的情况下，在OJ上运行所用的时间不会超过0.5s，运行所用的空间不会超过12MB，也就是说，选手实际可用的时间<strong>至少为0.5s</strong>，实际可用的空间<strong>至少为500MB</strong>。</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>

# 下载


<p><a href="/download.php?type=problem&amp;id=444">交互库下载</a></p>
