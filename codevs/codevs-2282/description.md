<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>C国有n座城市，城市之间通过m条<strong>单向</strong>道路连接。一条路径被称为最短路，当且仅当不存在从它的起点到终点的另外一条路径总长度比它小。两条最短路不同，当且仅当它们包含的道路序列不同。我们需要对每条道路的重要性进行评估，评估方式为计算有多少条不同的最短路经过该道路。现在，这个任务交给了你。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数n、m</p>
<p>接下来m行每行包含三个正整数u、v、w，表示有一条从u到v长度为w的道路</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出应有m行，第i行包含一个数，代表经过第i条道路的最短路的数目对<strong>1000000007</strong><strong>取模</strong>后的结果</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4<br>1 2 5<br>2 3 5<br>3 4 5<br>1 4 8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br>3<br>2<br>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%的数据满足：n≤15、m≤30</p>
<p>60%的数据满足：n≤300、m≤1000</p>
<p>100%的数据满足：n≤1500、m≤5000、w≤10000</p>
</div>
</div>