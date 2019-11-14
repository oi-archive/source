<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>如果某个无向连通图的任意一条边至多只出现在一条简单回路（simple cycle）里，我们就称这张图为仙人图（cactus）。所谓简单回路就是指在图上不重复经过任何一个顶点的回路。</p>
<p>显然，仙人图上的每条边，或者是这张仙人图的桥（bridge），或者在且仅在一个简单回路里，两者必居其一。定义在图上两点之间的距离为这两点之间最短路径的距离。定义一个图的直径为这张图相距最远的两个点的距离。现在我们假定仙人图的每条边的权值都是1，你的任务是求出给定的仙人图的直径。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包括两个整数n和m（1≤n≤50000以及0≤m≤10000）。其中n代表顶点个数，我们约定图中的顶点将从1到n编号。</p>
<p>接下来一共有m行。代表m条路径。每行的开始有一个整数k（2≤k≤1000），代表在这条路径上的顶点个数。接下来是k个1到n之间的整数，分别对应了一个顶点，相邻的顶点表示存在一条连接这两个顶点的边。一条路径上可能通过一个顶点好几次，比如对于第一个样例，第一条路径从3经过8，又从8返回到了3，但是我们保证所有的边都会出现在某条路径上，而且不会重复出现在两条路径上，或者在一条路径上出现两次。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只需输出一个数，这个数表示仙人图的直径长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>15 3</p>
<p>9 1 2 3 4 5 6 7 8 3</p>
<p>7 2 9 10 11 12 13 10</p>
<p>5 2 14 9 15 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤n≤50000以及0≤m≤10000</p>
</div>
</div>