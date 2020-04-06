# 题目描述

<p>新年的钟声即将敲响，鸡年即将到来！在计算鸡们的进攻下，猴腮雷只能夹着尾巴逃进了花果山，于是垫子计算鸡率领着一支突鸡队潜入花果山活捉猴腮雷。</p>
<p>然而猴腮雷非常狡猾，花果山住着他很多个六耳猴腮雷兄弟，长得跟自己几乎一模一样。一时间，突鸡队不知道哪个才是他们真的猴腮雷。</p>
<p>这时，突击队里的同构判定鸡发话了：“我来吧”。</p>
<p>在同构判定鸡眼里，世界都是离散的图，判定哪个是真的猴腮雷就转化为了判定两个无向图是否同构。对于两个无向图我们称他们同构当且仅当我们可以将其中一个图的结点重新编号，使得这两个图完全一样。</p>
<p>同构判定鸡掌握了 $6$ 个强有力的图同构判定算法，然而每个算法都存在一定的缺陷。缺陷在于，给定两个同构的图每个算法确实能判定出这两个图是同构，但是给定两个不同构的图该算法也有可能报告说这两个图是同构的。</p>
<p>然而同构判定鸡现在自信满满并没有意识到自己的错误所在。现在，请你给出两个图，证明他们不同构，并且使得这 $6$ 个算法都误以为他们是同构的。</p>

# 图同构判定算法


<p>共有 $6$ 个图同构判定算法，简要描述如下：</p>
<div class="table-responsive">
<table class="table table-bordered table-vertical-middle"><thead><tr><th class="text-center" style="width:6em;">算法编号</th>
<th class="text-center" style="width:4em;">分数</th>
<th>简要描述</th>
</tr></thead><tbody><tr><td class="text-center">1</td><td class="text-center">7</td><td>仅检查结点数及边数是否一致</td>
</tr><tr><td class="text-center">2</td><td class="text-center">13</td><td>首先仅检查结点数及边数，然后结点数很小时使用暴力，否则视为同构</td></tr><tr><td class="text-center">3</td><td class="text-center">19</td><td>初始每个结点颜色相同，每次对于每个结点结合自身的颜色和周围邻居的颜色编码产生新的颜色，反复迭代直至稳定。将最后每个图所得颜色进行排序，若相同则视为同构</td></tr><tr><td class="text-center">4</td><td class="text-center">21</td><td>与算法 3 类似，只是用结点间最短距离信息初始化结点颜色</td></tr><tr><td class="text-center">5</td><td class="text-center">17</td><td>枚举一个图中的一个固定的结点与另一个图中哪个结点对应，将他们分别染成特殊的颜色，其它结点颜色照常初始化，再用算法 3 中的迭代。若存在一种对应使得最后所得颜色相同，则视为同构</td></tr><tr><td class="text-center">6</td><td class="text-center">23</td><td>一种基于邻接矩阵的整数次幂的迹的哈希算法</td></tr></tbody></table></div>

<p>请参考“测评库下载”中的 grader.cpp 的具体代码来更好地理解算法流程。</p>

# 任务


<p>本题是一道交互式试题。</p>
<p>本题仅支持 C++，请包含头文件 isomorphism.h，见“测评库下载”。</p>
<p>交互库里内置了一个结构体 graph 用来存储无向图，选手需要通过 propose 函数传递两个 graph 类型的结构体给交互库，并证明这两个图是不同构的。</p>
<p>证明的方式如下：</p>
<ul><li>交互库收到选手传递的两个图 $A, B$。</li>
<li>重复如下过程 $50$ 次：<ul><li>从 $A, B$ 中随机选择一个图 $G$</li>
<li>随机将 $G$ 中的边打乱顺序，并随机将 $G$ 的结点编号打乱顺序</li>
<li>将 $G$ 回传给选手，让选手判断 $G$ 到底是 $A$ 还是 $B$</li>
</ul></li>
</ul><p>如果 $A, B$ 是同构的，那么选手每次判断时只能依靠运气，成功 $50$ 次的概率不会超过 $2^{-50}$。所以经过这个证明过程之后，我们就有超过 $1 - 2^{-50}$ 的把握认为这两个图是不同构的了。</p>
<p>具体来说，选手需要编写两个函数 hack 和 identify，以指出同构判定鸡的错误。</p>
<ul><li>hack()<ul><li>无参数，无返回值，选手需要在这里生成两个图 $A, B$，并通过 propose 函数传递给交互库。</li>
</ul></li>
<li>identify(g)<ul><li>$g$：一个 graph 类型的结构体，对应前文的 $G$。</li>
<li>返回值：返回一个等于 $1$ 或 $2$ 的整数。如果是 $1$ 则表示 $G$ 与 $A$ 同构，如果是 $2$ 则表示 $G$ 与 $B$ 同构。</li>
</ul></li>
</ul><p>你可以调用 propose 函数恰好一次以将你生成的图传递给交互库</p>
<ul><li>propose(a, b)<ul><li>$a$：一个 graph 类型的结构体，对应前文的 $A$。</li>
<li>$b$：一个 graph 类型的结构体，对应前文的 $B$。</li>
</ul></li>
</ul><p><strong>由于本题没有样例，比赛进行期间仅会检查你输出的图是否合法，若合法则得满分，比赛结束后会进行最终评测。</strong></p>
<p><strong>请勿作出攻击交互库的行为，若被发现将记 $0$ 分处理。</strong></p>

# 实现细节


<p>具体各接口定义如下：</p>
<pre><code class="sh_cpp">struct graph
{
    int n;
    std::vector&lt; std::pair&lt;int, int&gt; &gt; e;
};

void hack();
void propose(graph a, graph b);
int identify(graph g);</code></pre>

# 限制与约定


<p>选手给出的图必须是简单无向连通图，且结点数不能超过 $50$。</p>
<p>我们给出了一个参考的样例测评库 grader.cpp 及一个样例程序 sample.cpp。样例测评库中自带了图的合法性检查及题目中提到的 $6$ 个算法。请注意最终测评时 $6$ 个算法的运行不会占用选手的程序运行时间。</p>
<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$1\texttt{s}$</p>
<p><strong>空间限制：</strong>$256\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=286">测评库下载</a></p>
