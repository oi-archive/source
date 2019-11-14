<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个无向图G，每个点有个权值，每条边有一个颜色。这个无向图满足以下两个条件：<br>1. 对于任意节点连出去的边中，相同颜色的边不超过两条。<br>2. 图中不存在同色的环，同色的环指相同颜色的边构成的环。<br>在这个图上，你要支持以下三种操作：<br>0. 修改一个节点的权值。<br>1. 修改一条边的颜色。<br>2. 查询由颜色c的边构成的图中，所有可能在节点u到节点v之间的简单路径上的节点的权值的最大值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含四个正整数N, M, C, K，其中N为节点个数，M为边数，C为边的颜色数，K为操作数。<br>接下来N行，每行一个正整数vi，为节点i的权值。<br>之后M行，每行三个正整数u, v, w，为一条连接节点u和节点v的边，颜色为w。满足1 ≤ u, v ≤ N，0 ≤ w &lt; C，保证u ≠ v，且任意两个节点之间最多存在一条边(无论颜色)。<br>最后K行，每行表示一个操作。每行的第一个整数k表示操作类型。<br>0. k = 0为修改节点权值操作，之后两个正整数x和y，表示将节点x的权值vx修改为y。<br>1. k = 1为修改边的颜色操作，之后三个正整数u, v和w，表示将连接节点u和节点v的边的颜色修改为颜色w。满足0 ≤ w &lt; C。<br>2. k = 2为查询操作，之后三个正整数c, u和v，表示查询所有可能在节点u到节点v之间的由颜色c构成的简单路径上的节点的权值的最大值。如果不存在u和v之间不存在由颜色c构成的路径，那么输出“-1”。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含若干行，每行输出一个对应的信息。<br />1. 对于修改节点权值操作，不需要输出信息。<br />2. 对于修改边的颜色操作，按以下几类输出：<br />a) 若不存在连接节点u和节点v的边，输出&ldquo;No such edge.&rdquo;。<br />b) 若修改后不满足条件1，不修改边的颜色，并输出&ldquo;Error 1.&rdquo;。<br />c) 若修改后不满足条件2，不修改边的颜色，并输出&ldquo;Error 2.&rdquo;。<br />d) 其他情况，成功修改边的颜色，并输出&ldquo;Success.&rdquo;。<br />输出满足条件的第一条信息即可，即若同时满足b和c，则只需要输出&ldquo;Error 1.&rdquo;。<br />3. 对于查询操作，直接输出一个整数。 第 5</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 5 2 7<br>1<br>2<br>3<br>4<br>1 2 0<br>1 3 1<br>2 3 0<br>2 4 1<br>3 4 0<br>2 0 1 4<br>1 1 2 1<br>1 4 3 1<br>2 0 1 4<br>1 2 3 1<br>0 2 5<br>2 1 1 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4<br>Success.<br>Error 2.<br>-1<br>Error 1.<br>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据规模】<br>对于30%的数据：N ≤ 1000，M ≤ 10000，C ≤ 10，K ≤ 1000。<br>另有20%的数据：N ≤ 10000，M ≤ 100000，C = 1，K ≤ 100000。<br>对于100%的数据：N ≤ 10000，M ≤ 100000，C ≤ 10，K ≤ 100000。</p>
</div>
</div>