<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>放假了，小Z觉得呆在家里特别无聊，于是决定一个人去游乐园玩。进入游乐园后，小Z看了看游乐园的地图，发现可以将游乐园抽象成有n个景点、m条道路的无向连通图，且该图中至多有一个环（即m只可能等于n或者n-1）。小Z现在所在的大门也正好是一个景点。小Z不知道什么好玩，于是他决定，从当前位置出发，每次随机去一个和当前景点有道路相连的景点，并且同一个景点不去两次（包括起始景点）。贪玩的小Z会一直游玩，直到当前景点的相邻景点都已经访问过为止。小Z所有经过的景点按顺序构成一条非重复路径，他想知道这条路径的期望长度是多少？小Z把游乐园的抽象地图画下来带回了家，可是忘了标哪个点是大门，他只好假设每个景点都可能是大门（即每个景点作为起始点的概率是一样的）。同时，他每次在选择下一个景点时会等概率地随机选择一个还没去过的相邻景点。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行是两个整数n和m，分别表示景点数和道路数。 接下来行，每行三个整数Xi, Yi, Wi，分别表示第i条路径的两个景点为Xi, Yi，路径长Wi。所有景点的编号从1至n，两个景点之间至多只有一条道路。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>共一行，包含一个实数，即路径的期望长度（5位小数）。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>4 3 </span><br><span>1 2 3 </span><br><span>2 3 1 </span><br><span>3 4 4</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>6.00000</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>样例数据中共有6条不同的路径:<br> 路径 长度 概率 </span><br><span>1--&gt;4 8 1/4 </span><br><span>2--&gt;1 3 1/8 </span><br><span>2--&gt;4 5 1/8 </span><br><span>3--&gt;1 4 1/8 </span><br><span>3--&gt;4 4 1/8 </span><br><span>4--&gt;1 8 1/4 </span><br><span>因此期望长度 = 8/4 + 3/8 + 5/8 + 4/8 + 4/8 + 8/4 = 6.00</span></p>
<p> </p>
<p><span>对于100%的数据，1 &lt;= Wi &lt;= 100。<br> 测试点编号 n               备注 </span><br><span>1             n=10          保证图是链状 </span><br><span>2             n=100        只有节点1的度数大于2 </span><br><span>3             n=1000      / </span><br><span>4             n=100000  /</span></p>
<p><span>5             n=100000  / </span><br><span>6             n=10          / </span><br><span>7             n=100       环中节点个数&lt;=5 </span><br><span>8             n=1000     环中节点个数&lt;=10 </span><br><span>9             n=100000 环中节点个数&lt;=15 </span><br><span>10           n=100000 环中节点个数&lt;=20 </span></p>
</div>
</div>