<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>本题的目标是求一个点数无穷的无向图的桥。这个无向图具有如下性质：</p>
<p>(1)这个图是一个连通图。</p>
<p>(2)这个图的所有节点分为若干层，分别是第 1 层、第 2 层、第 3 层......</p>
<p>    共有无穷层，每层共有 n 个节点。为了描述方便，以下用(i, x)表示</p>
<p>    第 i 层的 x 号节点。</p>
<p>(3)同一层内的节点可以相互连边，相邻两层的节点之间可以相互连边，</p>
<p>    除此之外，其他节点之间不能相互连边。</p>
<p>(4)如果(i, x)与(i, y)之间有一条权值为 d 的边，那么(j, x)与(j, y)之间也</p>
<p>    有一条边，它的权值为 0.9<sup>j-i</sup>d，其中 j 为任意正整数。</p>
<p>(5)如果(i, x)与(i + 1, y)之间有一条权值为 的边，那么(j, x)与(j + 1, y)</p>
<p>    之间也有一条边，它的权值为 0.9<sup>j-i</sup>d，其中 j 为任意正整数。</p>
<p>如下所示的无向图就符合上面的所有性质。</p>
<p>一个点数无穷的无向图是连通的，当且仅当对于图中的任意两个节点都存在</p>
<p>一条路径将它们连接起来。而一条边是桥，当且仅当这条边被删去后整个图不连</p>
<p>通。</p>
<p>请你编写程序读入这个点数无穷的连通图，求出其中所有桥的权值之和。例</p>
<p>如，在上图中，粗线所示的边就是该图唯一的桥，因此上图中桥的权值之和为 1。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<div>
<p>第一行包括三个由空格隔开的非负整数 n、m1、m2。</p>
<p>从第 2 行到第 m1 + 1 行，每行有三个正整数 x、y、d，表示(1, x)与(1, y)之间<span style="">有一条权值为 d 的边。</span></p>
</div>
<div>
<p>从第 m1 + 2 行到第 m1 + m2 + 1 行，每行有三个正整数 x、y、d，表示(1, x)</p>
<p>与(2, y)之间有一条权值为 d 的边。</p>
<p>每行的三个整数之间都用一个空格隔开。图中两个点 x 和 y 之间可能有多于<span style="">1 条边连接，一条边连接的两个节点可能相同。</span></p>
</div>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">只有一行，包含一个实数，即所有桥的权值之和，四舍<span style="font-size: 10px;">五入保留两位小数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】</p>
<p>3 1 3</p>
<p>1 2 4</p>
<p>1 2 5</p>
<p>2 3 3</p>
<p>3 3 1</p>
<p>【样例输入2】</p>
<p>1 1 1</p>
<p>1 1 100</p>
<p>1 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】</p>
<p>1.00</p>
<p>【样例输出2】</p>
<p>10.00</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于100%的数据,n≤300000,m1,m2≤500000,d≤100.</p>
</div>
</div>