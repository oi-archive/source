<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    小 Q最近学习了一些图论知识。根据课本，有如下定义。 <br>    树：无回路且连通的无向图，每条边都有正整数的权值来表示其长度。如果一棵树有N个节点，可以证明其有且仅有 N-1 条边。 <br>    路径：一棵树上，任意两个节点之间最多有一条简单路径。我们用 dis(a,b)表示点 a 和点 b 的路径上各边长度之和。称 dis(a,b)为 a、b 两个节点间的距离。 <br>    直径：一棵树上，最长的路径为树的直径。树的直径可能不是唯一的。 <br>    现在小 Q 想知道，对于给定的一棵树，其直径的长度是多少，以及有多少条边满足所有的直径都经过该边。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数 N，表示节点数。 <br>接下来 N-1行，每行三个整数 a, b, c，表示点 a和点b之间有一条长度为 c的无向边。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共两行。第一行一个整数，表示直径的长度。第二行一个整数，表示被所有直径经过的边的数量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6 <br>3 1 1000 <br>1 4 10 <br>4 2 100 <br>4 5 50 <br>4 6 100</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1110 <br>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】 <br>直径共有两条，3 到 2 的路径和 3 到 6 的路径。这两条直径都经过边(3, 1)和边(1, 4)。<br><br></p>
<p>【数据规模和约定】 <br>对于 20%的测试数据：N≤100 <br>对于 40%的测试数据：N≤1000 <br>对于 70%的测试数据：N≤100000 <br>对于 100%的测试数据：2≤N≤200000，所有点的编号都在 1..N 的范围内，边的权值≤10<sup>9</sup>。</p>
<p> </p>
</div>
</div>