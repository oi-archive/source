# 题目描述

<p>在经过了多次失败后，跳蚤国王终于成功地制造出了第一个也是唯一一个最强跳蚤——跳蚤属性储备的不足使得量产最强跳蚤的计划化作了泡影。但是即使只有一个最强跳蚤，战争的局势还是渐渐地被逆转了——最强跳蚤每次可以带着几百只跳蚤跳到 pion 吧的腹地进行骚扰。腹背受敌的人类渐渐陷入了劣势。</p>
<p>为局势所迫，人类的领袖_叫我猪猪侠决定和跳蚤国一样，制造属于自己阵营的超级士兵——这个计划被人们称作人类补完计划。</p>
<p>每一个人的遗传物质中都有许多的基因节点，基因节点之间又被基因链相连——这可以看做一张 $n$ 个点 $m$ 条边的<strong>无向图</strong>——它们构成了人类的基因图。然而在人类的基因图中，并不是所有的都是优秀的基因，例如傲慢、妒忌、暴怒、懒惰、贪婪、饕餮和色欲，它们就是负面的。</p>
<p>在人类补完计划中，人类将删去基因图中不好的基因链以及没有被任何基因链连接的孤立的基因节点，来达成补全人类优秀基因的目的。</p>
<p>为了得到最优的方案，科学家们需要对人类的基因图进行多方面的评估。其中有一项简要来讲是这样的，就是给出一张$n$个点$m$条边的基因图，对于一个边集的子集$S_e$，我们把所有与$S_e$中<strong>至少</strong>一条边相邻的点形成的集合称为$S_v$，$S_e$被称为<strong>好的</strong>当且仅当：</p>
<ol><li>$|S_e| = |S_v|$。</li>
<li>对于$S_v$中不同的两个点$x$和$y$，存在一条从$x$到$y$的路径使得路径中的边都属于$S_e$。</li>
</ol><p>设所有与$S_e$中<strong>大于</strong>一条边相邻的点的数量为$w$，那么这个边集的<strong>权值</strong>为$2 ^ w$。一张基因图的权值是所有<strong>好的</strong>边集的权值和。</p>
<p>现在_叫我猪猪侠想要知道他自己的基因图的权值，但是因为战争事务实在太过繁杂，所以他决定让你——一个刚刚从前线抓来的为跳蚤办事的人类叛徒来帮他计算答案。</p>

# 输入格式


<p>第一行两个正整数 $n, m$，含义如题意所述。</p>
<p>接下来的$m$行中，第$i$行有两个整数$x_i, y_i$，表示$x_i$与$y_i$之间有一条无向边。</p>

# 输出格式


<p>一行一个整数，表示这张基因图的权值对$998244353$取模的值。</p>

# 样例一


<h4>input</h4>
<pre>3 3
1 3
2 3
1 2
</pre>

<h4>output</h4>
<pre>8
</pre>

<h4>explanation</h4>
<p>唯一的好的边集就是所有边组成的集合，由于所有点都与边集中两条边相邻，所以权值为$2 ^ 3 = 8$。</p>

# 样例二


<h4>input</h4>
<pre>3 2
1 2
1 3
</pre>

<h4>output</h4>
<pre>0
</pre>

<h4>explanation</h4>
<p>不存在好的边集。</p>

# 样例三


<h4>input</h4>
<pre>4 4
1 2
1 3
2 3
1 4
</pre>

<h4>output</h4>
<pre>16
</pre>

<h4>explanation</h4>
<p>整数$x$表示输入的第$x$条边。
好的边集为$\{1, 2, 3\}$, $\{1, 2, 3, 4\}$，在两个边集中$4$号点分别与0条和1条边相邻，都不会算入$w$中，而其他三个点都至少与2条边相邻，因此两个边集的权值均为$8$，答案为$8 + 8 = 16$。</p>

# 样例四


<h4>input</h4>
<pre>5 5
1 2
1 3
2 3
1 4
4 5
</pre>

<h4>output</h4>
<pre>32
</pre>

<h4>explanation</h4>
<p>好的边集为$\{1, 2, 3\}$, $\{1, 2, 3, 4\}$, $\{1, 2, 3, 4, 5\}$，前两个边集的权值为8，最后一个边集的权值为16，答案为$8 + 8 + 16 = 32$。</p>

# 样例五


<h4>input</h4>
<pre>6 10
5 3
4 3
2 3
1 6
5 6
2 6
1 5
1 4
6 3
3 1
</pre>

<h4>output</h4>
<pre>4544
</pre>


# 样例六


<p>见样例数据下载，这组数据中$n = 14$，$m = 90$，请注意答案要对$998244353$取模。</p>

# 限制与约定


<p>每组测试数据的限制与约定如下所示：</p>
<div class="table-responsive">
<table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>测试点编号</th>
<th>n</th>
<th>m</th>
</tr></thead><tbody><tr><td>1</td><td rowspan="6">$n \le 11$</td><td rowspan="1">$m \le 20$</td></tr><tr><td>2</td><td rowspan="1">保证每个点最多只能直接或间接到达6个其他的点。</td></tr><tr><td>3</td><td rowspan="8"></td></tr><tr><td>4</td></tr><tr><td>5</td></tr><tr><td>6</td></tr><tr><td>7</td><td rowspan="4">$n \le 14$</td></tr><tr><td>8</td></tr><tr><td>9</td></tr><tr><td>10</td></tr><tr><td>11</td><td rowspan="4">$n \le 15$</td><td rowspan="1">$m = \frac{n(n - 1)}{2}$</td></tr><tr><td>12</td><td rowspan="3"></td></tr><tr><td>13</td></tr><tr><td>14</td></tr><tr><td>15</td><td rowspan="6">$n \le 16$</td><td rowspan="1">$m = \frac{n(n - 1)}{2}$</td></tr><tr><td>16</td><td rowspan="5"></td></tr><tr><td>17</td></tr><tr><td>18</td></tr><tr><td>19</td></tr><tr><td>20</td></tr></tbody></table></div>

<p>对于所有数据， $1 \le n \le 16$, $0 \le m \le \frac{n(n - 1)}{2}$。</p>
<p>$1 \le x_i, y_i \le n$，$x_i \ne y_i$，两个点之间最多只有一条边。</p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=193">样例数据下载</a></p>
