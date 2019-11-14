<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在社交网络（social network）的研究中，我们常常使用图论概念去解释一些 社会现象。 不妨看这样的一个问题。在一个社交圈子里有 n 个人，人与人之间有不同程 度的关系。我们将这个关系网络对应到一个 n 个结点的无向图上，两个不同的人 若互相认识，则在他们对应的结点之间连接一条无向边，并附上一个正数权值 c， c 越小，表示两个人之间的关系越密切。 我们可以用对应结点之间的最短路长度来衡量两个人 s 和 t 之间的关系密切 程度，注意到最短路径上的其他结点为 s 和 t 的联系提供了某种便利，即这些结 点对于 s 和 t 之间的联系有一定的重要程度。我们可以通过统计经过一个结点 v 的最短路径的数目来衡量该结点在社交网络中的重要程度。 考虑到两个结点 A 和 B 之间可能会有多条最短路径。我们修改重要程度的定 义如下： 令 Cs,t表示从 s 到 t 的不同的最短路的数目， Cs,t(v)表示经过 v 从 s 到 t 的最短 路的数目；则定义I（v）为结点 v 在社交网络中的重要程度。 为了使 I(v)和 Cs,t(v)有意义，我们规定需要处理的社交网络都是连通的无向 图，即任意两个结点之间都有一条有限长度的最短路径。 <br>现在给出这样一幅描述社交网络的加权无向图，请你求出每一个结点的重要程度。</p>

<img src="/source/codevs/codevs-1796/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzk2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTc5Ni5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件中第一行有两个整数，n 和 m，表示社交网络中结点和无向边的数 目。在无向图中，我们将所有结点从 1 到 n 进行编号。 接下来 m 行，每行用三个整数 a, b, c 描述一条连接结点 a 和 b，权值为 c 的 无向边。注意任意两个结点之间最多有一条无向边相连，无向图中也不会出现自 环（即不存在一条无向边的两个端点是相同的结点）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件包括 n 行，每行一个实数，精确到小数点后 3 位。第 i 行的实数表 示结点 i 在社交网络中的重要程度</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4</p>
<p>1 2 1</p>
<p>2 3 1</p>
<p>3 4 1</p>
<p>4 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1.000</p>
<p>1.000</p>
<p>1.000</p>
<p>1.000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见图</p>
</div>
</div>