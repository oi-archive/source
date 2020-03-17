# 题目描述

<p>Scape非常喜欢在和Mythological逛公园的时候，讲时间复杂度的知识给她听。但是他很快便伤心地发现Mythological对复杂度的兴趣，还没有旁边的蚯蚓列队表演的兴趣高，只好向whx诉苦。</p>
<p>whx面对Scape的疑惑，告诉他，重要的是Mythological喜欢什么，而不是他自己喜欢什么。Scape发现Mythological特别喜欢玩Geometry Dash，所以特意下载了一个来玩。</p>
<p>打开游戏，Scape发现平面直角坐标系上有 $n$ 个红点 $P_0,P_1,\cdots,P_{n-1}$ 和 $m$ 个蓝点 $Q_0,Q_1,\cdots,Q_{m-1}$。（其中这 $n+m$ 个点和原点 $O$ 一共 $n+m+1$ 个点中，任意三点不共线。）</p>
<p>Scape很快反应过来，以原点 $O$ 和任意两个红点 $P_i,P_j$ 为顶点构成的三角形 $OP_iP_j$ 一共有 ${n(n-1)\over 2}$ 个。</p>
<p>如果一个三角形的内部不包含任何蓝点，Scape称该三角形是空的，否则，Scape称该三角形是非空的。</p>
<p>Scape的任务是判断以原点和任意两个红点为顶点构成的 ${n(n-1)\over 2}$ 个三角形中，每个三角形是空的还是非空的。为了证明一个三角形非空，对于每个非空的三角形，请给出任意一个在该三角形内部的蓝点 $Q_k$（$0\le k &lt; m$）。</p>

# 任务


<p>你需要编写一个函数 check_triangles，以完成题目的任务：</p>
<ul><li>check_triangles(n, m, rx, ry, bx, by, result)<ul><li>n: 坐标系上给出的红点个数。</li>
<li>m: 坐标系上给出的蓝点个数。</li>
<li>rx: 大小为 $n$ 的数组；rx[i] 表示红点 $P_i$ 的横坐标，其中 $0\le i &lt; n$。</li>
<li>ry: 大小为 $n$ 的数组；ry[i] 表示红点 $P_i$ 的纵坐标，其中 $0\le i &lt; n$。</li>
<li>bx: 大小为 $m$ 的数组；bx[i] 表示蓝点 $Q_i$ 的横坐标，其中 $0\le i &lt; m$。</li>
<li>by: 大小为 $m$ 的数组；by[i] 表示蓝点 $Q_i$ 的纵坐标，其中 $0\le i &lt; m$。</li>
<li>result: 大小为 $n\times n$ 的二维数组；你需要将三角形 $OP_iP_j$（$0\le i &lt; j &lt; n$）的判断结果存放到 result[i][j] 中：若三角形 $OP_iP_j$ 非空，则将任意一个在其内部的蓝点 $Q_k$ 的编号 $k$ 存放到 result[i][j] 中，否则将 $-1$ 存放到 result[i][j] 中。你不应当访问 $0\le i &lt; j &lt; n$ 范围以外的 result[i][j]。</li>
</ul></li>
</ul>
# 实现细节


<p>本题只支持 C/C++。</p>
<p>你只能提交一个源文件实现如上所述的 check_triangles 函数，并且遵循下面的命名和接口。你需要包含头文件 triangles.h。</p>
<pre><code class="sh_cpp">void check_triangles(int n, int m, int *rx, int *ry, int *bx, int *by, int **result);</code></pre>
<p>如果有不清楚的地方，见样例及测评库下载，<strong>内附了样例程序</strong>。</p>

# 评测方式


<p>评测系统将读入如下格式的输入数据：</p>
<ol><li>第 $1$ 行：数据类型 $\mathrm{type}$（值为 $0$ 或 $1$）。</li>
<li>第 $2$ 行：$n$, $m$。</li>
<li>第 $3+i$ 行：rx[i], ry[i]。</li>
<li>第 $3+n+i$ 行：bx[i], by[i]。</li>
</ol><p>对于样例数据，$\mathrm{type}=1$，评测系统将会输出 $n-1$ 行，其中第 $i+1$ 行包含 $n-i-1$ 个整数，依次为 result[i][i+1], result[i][i+2], ..., result[i][n-1] 的值。</p>
<p>对于测试数据，$\mathrm{type}=0$，评测系统将输出一行一个整数，表示根据数据和 result 数组计算得到的校验和。</p>
<p>注意：$\mathrm{type}=0$ 时，下发的测评库计算的校验和为 result[i][j]（$0\le i &lt; j &lt; n$）中非负数的个数。<strong>最终评测时，校验和计算方法与下发的测评库计算方法不同。</strong></p>

# 样例一


<h4>input</h4>
<pre>1
4 3
3 3
-2 4
5 -5
-4 -2
3 -1
1 0
-3 -2

</pre>

<h4>output</h4>
<pre>-1 0 -1
1 -1
2

</pre>

<h4>explanation</h4>
<p>如下图所示：</p>
<p><img class="img-responsive center-block" src="//img.uoj.ac/problem/326/326.png" alt="样例解释" width="300"/></p>
<p>样例输出中 result[0][2]=0 可以改成 1，这是因为 $B_1(1,0)$ 同样在以 $O(0,0),A_0(3,3),A_2(5,-5)$ 为顶点的三角形 $OA_0A_2$ 内部。</p>

# 样例二


<p>见样例及测评库下载。该样例输出共包含 $17926$ 个非负数。</p>

# 样例三


<p>见样例及测评库下载。该样例输出共包含 $38756$ 个非负数。</p>

# 限制与约定


<p>对于所有数据，$2\le n\le 4000$，$1\le m\le 4000$，所有点的横、纵坐标均在 $[-10^9,10^9]$ 范围内。</p>
<p>为避免精度误差，保证任意三点构成的夹角在 $[10^{-12}\pi,\pi-10^{-12}\pi]$ 之间。</p>
<div class="table-responsive">
 <table class="table table-bordered table-text-center table-vertical-middle"><thead><tr><th>子任务</th>
    <th>分值</th>
    <th>$n$</th>
    <th>$m$</th>
   </tr></thead><tbody><tr><td>1</td>
    <td>32</td>
    <td>$\le 200$</td>
    <td>$\le 200$</td>
   </tr><tr><td>2</td>
    <td>46</td>
    <td>$\le 1200$</td>
    <td>$\le 1200$</td>
   </tr><tr><td>3</td>
    <td>22</td>
    <td>$\le 4000$</td>
    <td>$\le 4000$</td>
   </tr></tbody></table></div>

<p><a href="/faq">交互式类型的题目怎么本地测试</a></p>
<p><strong>时间限制：</strong>$2\texttt{s}$</p>
<p><strong>空间限制：</strong>$512\texttt{MB}$</p>

# 下载


<p><a href="/download.php?type=problem&amp;id=326">样例及测评库下载</a></p>
