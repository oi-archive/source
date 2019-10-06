# 题目描述

<p>这是一道<strong>交互题</strong>。</p>
<p>跳蚤国国土面积约五万万平方千米，那里生活着四万万快乐的跳蚤。这是一个晴朗的早晨，为了丰富跳蚤们的生活，跳蚤国王组织了一场跳高比赛，共有 $m$ 只跳蚤参赛。</p>
<p>比赛进入准备环节。$m$ 只跳蚤站成了一行，编号为 $1, \dots, m$。跳蚤共有 $n$ 种跳高姿势，编号为 $1, \dots, n$，跳高时跳蚤需要选择一种跳高姿势。</p>
<p>然而跳蚤国王的助手伏特早就看穿了一切，他经过长期的观察研究发现第 $i$ 种跳高姿势可以用 $3$ 个参数 $a_i, b_i, c_i$ 表示。如果第 $k$ 只跳蚤使用第 $i$ 种跳高姿势跳高，那么它将跳出 $a_i k^2 + b_i k + c_i$ 米的好成绩。这里保证 $a_i &gt; 0$ 且 $b_i^2 - 4 a_i c_i \leq 0$。</p>
<p>比赛开始了，但是跳蚤们的心态都不太好，纷纷采取保守策略选取那个使自己跳得<strong>最矮</strong>的跳高姿势进行跳跃。</p>
<p>然而突然间风停了，立刻起了雾霾，空气污染指数上了五位数。</p>
<p>这可难倒了跳蚤国王，他需要知道跳得<strong>最高</strong>的跳蚤的高度，然而他现在连自己的手都找不到在哪里了。于是跳蚤国王只好向伏特求助，然而伏特本来想手算出各个跳蚤的成绩，结果发现自己忘记了每个跳高姿势对应的三个参数！</p>
<p>于是跳蚤国王很无奈，只好把伏特踹下裁判席让他去测量选手的成绩。跳蚤国王每次会问这样的问题：“伏特，第 $k$ 只跳蚤怎么样？” 伏特会去仔细观察一下第 $k$ 只跳蚤使用的跳高姿势得到该跳高姿势的三个参数 $a_i, b_i, c_i$，跑回来告诉跳蚤国王。</p>
<p>然而跳蚤国王推理能力太弱只能一个一个地按顺序问每只跳蚤的情况，让伏特跑断了腿，于是伏特找到了你。他想让你教教跳蚤国王，怎样询问不超过 $n$ 个问题就能知道跳得最高的跳蚤的高度？</p>

# 输入格式


<p>你需要编写一个函数 <code>find_max</code>，以确定跳得最高的跳蚤的高度。</p>
<ul><li><code>find_max(n, m)</code><ul><li><code>n</code>：跳高姿势的种类数 $n$。保证 $n \geq 1$。</li>
<li><code>m</code>：跳蚤的总数 $m$。保证 $m \geq 1$。</li>
<li>这个函数返回值应为跳得最高的跳蚤的高度。</li>
</ul></li>
</ul><p>你可以调用函数 <code>get</code> 以帮助你确定跳得最高的跳蚤的高度。我们会根据你调用这个函数的<strong>总次数</strong>评分。</p>
<ul><li><code>get(p, a, b, c)</code> 将查询第 $p$ 只跳蚤的跳高姿势的三个参数，分别赋值给 $a, b, c$。如果 $p$ 在 $[1, m]$ 范围之外，该函数将不进行任何操作。</li>
</ul>
# 实现细节


<p>本题只支持 C++。</p>
<p>你只能提交一个源文件实现如上所述的 <code>find_max</code> 函数，并且遵循下面的命名和接口。</p>
<p>你需要包含头文件 <code>flea.h</code>。</p>
<pre><code class="sh_cpp">long long find_max(int n, int m);</code></pre>
<p>函数 get 的接口信息如下。</p>
<pre><code class="sh_cpp">void get(int p, long long *a, long long *b, long long *c);</code></pre>
<p>函数将会把跳高姿势的三个参数分别赋值给 $a, b, c$ 所指向的变量。</p>
<p>如果有不清楚的地方，见样例及测评库下载，<strong>内附了样例程序</strong>。</p>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ol><li>第 $1$ 行: $n, m$</li>
<li>第 $1 + i$ 行（$1 \leq i \leq n$）：$a_i, b_i, c_i$。</li>
</ol><p>在 <code>find_max</code> 返回后，评测系统将输出你的答案以及 <code>get</code> 函数的总调用次数。</p>

# 样例一


<h4>input</h4>
<pre>3 1000000
326 -421505646 271727651175230
765 -593058832 140861873339701
291 -633539923 472231112710095

</pre>

<h4>output</h4>
<pre>146638735615726 3

</pre>

<h4>explanation</h4>
<p>第 $831493$ 只跳蚤跳得最高。</p>
<p>输出的第二个整数 3 为总调用次数，你可以认为这是一个调用了 3 次 <code>get</code> 函数的程序的输出。</p>

# 样例二


<p>见样例及测评库下载。</p>

# 限制与约定


<p>共 $10$ 个测试点，每个测试点 $10$ 分。设你的程序 <code>get</code> 函数的调用次数为 $t$。当 $t \leq n$ 时得 $10$ 分，否则当 $t \leq 5n$ 时得 $7$ 分，否则当 $t \leq 50n$ 时得 $4$ 分，否则不得分。</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>特殊限制</th>
</tr></thead><tbody><tr><td>1</td><td>$n = 10, m = 10$</td>
</tr><tr><td>2</td><td>$n = 1$</td></tr><tr><td>3</td><td>$n = 2$</td></tr><tr><td>4</td><td>$n = 3$</td></tr><tr><td>5</td><td rowspan="6">无</td></tr><tr><td>6</td></tr><tr><td>7</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr></tbody></table></div>

<p>对于所有测试点，$1 \leq n \leq 1000$，$1 \leq m \leq 10^6$。对于每个跳高姿势，$1 \leq a_i \leq 1000$，$\left \lvert b_i \right \rvert \leq 10^9$, $\left \lvert c_i \right \rvert \leq 10^{15}$，且 $b_i^2 - 4a_ic_i \leq 0$。</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=165">样例及测评库下载</a></p>
