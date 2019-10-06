# 题目描述

<p>本题的故事发生在魔力之都，在这里我们将为你介绍一些必要的设定。</p>
<p>魔力之都可以抽象成一个 $n$ 个节点、$m$ 条边的<strong>无向连通图</strong>（节点的编号从 $1$ 至 $n$）。我们依次用 $l,a$ 描述一条边的<strong>长度</strong>、<strong>海拔</strong>。</p>
<p>作为季风气候的代表城市，魔力之都时常有雨水相伴，因此道路积水总是不可避免的。由于整个城市的排水系统连通，因此<strong>有积水的边一定是海拔相对最低的一些边</strong>。</p>
<p>我们用<strong>水位线</strong>来描述降雨的程度，它的意义是：所有海拔<strong>不超过</strong>水位线的边都是<strong>有积水</strong>的。</p>

# 题目描述


<p>Yazid 是一名来自魔力之都的 OIer，刚参加完 ION2018 的他将踏上归程，回到他温暖的家。</p>
<p>Yazid 的家恰好在魔力之都的 $1$ 号节点。对于接下来 $Q$ 天，每一天 Yazid 都会告诉你他的出发点 $v$ ，以及当天的水位线 $p$。</p>
<p>每一天，Yazid 在出发点都拥有一辆<strong>车</strong>。这辆车由于一些故障不能经过有积水的边。Yazid 可以在任意节点下车，这样接下来他就可以步行经过有积水的边。但车会被留在他下车的节点并不会再被使用。</p>
<ul><li>需要特殊说明的是，第二天车会被重置，这意味着：<ul><li>车会在新的出发点被准备好。</li>
<li>Yazid 不能利用之前在某处停放的车。</li>
</ul></li>
</ul><p>Yazid 非常讨厌在雨天步行，因此他希望在完成回家这一目标的同时，最小化他<strong>步行经过的</strong>边的总长度。请你帮助 Yazid 进行计算。</p>
<p><em>本题的部分测试点将强制在线，具体细节请见【输入格式】和【子任务】。</em></p>

# 输入格式


<p>从标准输入读入数据。</p>
<p>单个测试点中包含多组数据。输入的第一行为一个非负整数 $T$，表示数据的组数。接下来依次描述每组数据，对于每组数据：</p>
<ul><li>第一行 $2$ 个非负整数 $n,m$，分别表示节点数、边数。</li>
<li>接下来 $m$ 行，每行 $4$ 个正整数 $u,v,l,a$，描述一条连接节点 $u,v$ 的、长度为 $l$、海拔为 $a$ 的边。<ul><li>在这里，我们保证 $1\leq u,v\leq n$。</li>
</ul></li>
<li>接下来一行 $3$ 个非负数 $Q,K,S$，其中 $Q$ 表示总天数，$K\in\left\{0,1\right\}$ 是一个会在下面被用到的系数，$S$ 表示的是可能的最高水位线。</li>
<li>接下来 $Q$ 行依次描述每天的状况。每行 $2$ 个整数 $v_0,p_0$ 描述一天：<ul><li>这一天的出发节点为 $v=\left(v_0+K\times lastans-1\right)\bmod n+1$。</li>
<li>这一天的水位线为 $p=\left(p_0+K\times lastans\right)\bmod \left(S+1\right)$。</li>
<li>其中 $lastans$ 表示上一天的答案（最小步行总路程）。特别地，我们规定第 $1$ 天时 $lastans=0$。</li>
<li>在这里，我们保证 $1\leq v_0\leq n$，$0\leq p_0\leq S$。</li>
</ul></li>
</ul><p>对于输入中的每一行，如果该行包含多个数，则用单个空格将它们隔开。</p>

# 输出格式


<p>输出到标准输出。</p>
<p>依次输出各组数据的答案。对于每组数据：</p>
<ul><li>输出 $Q$ 行每行一个整数，依次表示每天的最小步行总路程。</li>
</ul>
# 样例一


<h4>input</h4>
<pre>1
4 3
1 2 50 1
2 3 100 2
3 4 50 1
5 0 2
3 0
2 1
4 1
3 1
3 2

</pre>



<h4>output</h4>
<pre>0
50
200
50
150

</pre>


<h4>解释</h4>
<p>第一天没有降水，Yazid 可以坐车直接回到家中。</p>
<p>第二天、第三天、第四天的积水情况相同，均为连接 $1,2$ 号节点的边、连接 $3,4$ 号点的边有积水。</p>
<p>对于第二天，Yazid 从 $2$ 号点出发坐车只能去往 $3$ 号节点，对回家没有帮助。因此 Yazid 只能纯靠徒步回家。</p>
<p>对于第三天，从 $4$ 号节点出发的唯一一条边是有积水的，车也就变得无用了。Yazid 只能纯靠徒步回家。</p>
<p>对于第四天，Yazid 可以坐车先到达 $2$ 号节点，再步行回家。</p>
<p>第五天所有的边都积水了，因此 Yazid 只能纯靠徒步回家。</p>

# 样例二


<h4>input</h4>
<pre>1
5 5
1 2 1 2
2 3 1 2
4 3 1 2
5 3 1 2
1 5 2 1
4 1 3
5 1
5 2
2 0
4 0

</pre>



<h4>output</h4>
<pre>0
2
3
1

</pre>


<h4>解释</h4>
<p>本组数据强制在线。</p>
<p>第一天的答案是 $0$，因此第二天的 $v=\left( 5+0-1\right)\bmod 5+1=5$，$p=\left(2+0\right)\bmod\left(3+1\right)=2$。</p>
<p>第二天的答案是 $2$，因此第三天的 $v=\left( 2+2-1\right)\bmod 5+1=4$，$p=\left(0+2\right)\bmod\left(3+1\right)=2$。</p>
<p>第三天的答案是 $3$，因此第四天的 $v=\left( 4+3-1\right)\bmod 5+1=2$，$p=\left(0+3\right)\bmod\left(3+1\right)=3$。</p>

# 样例三


<p>见<a href="/download.php?type=problem&amp;id=393">下载目录</a>下的 <em>ex_3.in</em> 与 <em>ex_3.ans</em>。</p>

# 样例四


<p>见<a href="/download.php?type=problem&amp;id=393">下载目录</a>下的 <em>ex_4.in</em> 与 <em>ex_4.ans</em>。</p>

# 样例五


<p>见<a href="/download.php?type=problem&amp;id=393">下载目录</a>下的 <em>ex_5.in</em> 与 <em>ex_5.ans</em>。</p>

# 子任务


<p><em>所有测试点均保证 $T\leq 3$，所有测试点中的所有数据均满足如下限制：</em></p>
<ul><li><p>$n\leq 2\times 10^5$，$m\leq 4\times 10^5$，$Q\leq 4\times 10^5$，$K\in\left\{0,1\right\}$，$1\leq S\leq 10^9$。</p>
</li>
<li><p>对于所有边：$l\leq 10^4$，$a\leq 10^9$。</p>
</li>
<li><p>任意两点之间都直接或间接通过边相连。</p>
</li>
</ul><p><strong>为了方便你快速理解，我们在表格中使用了一些简单易懂的表述。在此，我们对这些内容作形式化的说明：</strong></p>
<ul><li><p>图形态：对于表格中该项为“一棵树”或“一条链”的测试点，保证 $m=n-1$。除此之外，这两类测试点分别满足如下限制：</p>
<ul><li><p>一棵树：保证输入的图是一棵树，即保证边不会构成回路。</p>
</li>
<li><p>一条链：保证所有边满足 $u+1=v$。</p>
</li>
</ul></li>
<li><p>海拔：对于表格中该项为“一种”的测试点，保证对于所有边有 $a=1$。</p>
</li>
<li><p>强制在线：对于表格中该项为“是”的测试点，保证 $K=1$；如果该项为“否”，则有 $K=0$。</p>
</li>
<li><p>对于所有测试点，如果上述对应项为“不保证”，则对该项内容不作任何保证。</p>
</li>
</ul><div class="table-responsive"><table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th rowspan="1">$n$</th><th rowspan="1">$m$</th><th rowspan="1">$Q=$</th><th rowspan="1">测试点</th><th rowspan="1">图形态</th><th rowspan="1">海拔</th><th rowspan="1">强制在线</th></tr></thead><tbody><tr><td rowspan="1">$\leq 1$</td><td rowspan="1">$\leq 0$</td><td rowspan="1">$0$</td><td rowspan="1">1</td><td rowspan="6">不保证</td><td rowspan="6">一种</td><td rowspan="10">否</td></tr><tr><td rowspan="1">$\leq 6$</td><td rowspan="1">$\leq 10$</td><td rowspan="1">$10$</td><td rowspan="1">2</td></tr><tr><td rowspan="1">$\leq 50$</td><td rowspan="1">$\leq 150$</td><td rowspan="1">$100$</td><td rowspan="1">3</td></tr><tr><td rowspan="1">$\leq 100$</td><td rowspan="1">$\leq 300$</td><td rowspan="1">$200$</td><td rowspan="1">4</td></tr><tr><td rowspan="1">$\leq 1500$</td><td rowspan="1">$\leq 4000$</td><td rowspan="1">$2000$</td><td rowspan="1">5</td></tr><tr><td rowspan="1">$\leq 200000$</td><td rowspan="1">$\leq 400000$</td><td rowspan="1">$100000$</td><td rowspan="1">6</td></tr><tr><td rowspan="3">$\leq 1500$</td><td rowspan="5">$=n-1$</td><td rowspan="3">$2000$</td><td rowspan="1">7</td><td rowspan="3">一条链</td><td rowspan="14">不保证</td></tr><tr><td rowspan="1">8</td></tr><tr><td rowspan="1">9</td></tr><tr><td rowspan="5">$\leq 200000$</td><td rowspan="5">$100000$</td><td rowspan="1">10</td><td rowspan="2">一棵树</td></tr><tr><td rowspan="1">11</td><td rowspan="1">是</td></tr><tr><td rowspan="3">$\leq 400000$</td><td rowspan="1">12</td><td rowspan="9">不保证</td><td rowspan="3">否</td></tr><tr><td rowspan="1">13</td></tr><tr><td rowspan="1">14</td></tr><tr><td rowspan="2">$\leq 1500$</td><td rowspan="2">$\leq 4000$</td><td rowspan="2">$2000$</td><td rowspan="1">15</td><td rowspan="6">是</td></tr><tr><td rowspan="1">16</td></tr><tr><td rowspan="4">$\leq 200000$</td><td rowspan="4">$\leq 400000$</td><td rowspan="2">$100000$</td><td rowspan="1">17</td></tr><tr><td rowspan="1">18</td></tr><tr><td rowspan="2">$400000$</td><td rowspan="1">19</td></tr><tr><td rowspan="1">20</td></tr></tbody></table></div>

<p><strong>为了优化你的阅读体验，我们在表格中把测试点的编号放在了中间，请注意这一点。</strong></p>
<p><strong>时间限制：</strong>$4\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 提示


<ul><li>样例 3 满足海拔为一种，且<strong>不</strong>强制在线。</li>
<li>样例 4 满足图形态为一条链，且强制在线。</li>
<li>样例 5 满足<strong>不</strong>强制在线。</li>
</ul>
# 下载


<p><a href="/download.php?type=problem&amp;id=393">样例数据下载</a></p>
