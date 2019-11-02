<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　当wek_deng学了SPFA之后，一直想验证自己的算法正确性。于是，Snakes给出了一个问题：给定一个有向图，求s到t的最短路径。wek_deng不太会做，于是把这道题公之于众，找你们来帮忙。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行，两个数，n,e，表示点数与边数。</p><p>　　第二行，两个数，s,t，意义如上。</p><p>　　接下来e行，每行为，u,v,w，表示从u到v有有向边，权值为w。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　一行，表示s到t的最短路径，如果s到t不连通则输出-1，如果s到t的最短路径会经过负环则输出&quot;Negative!&quot;（不包括引号）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2<br>1 2<br>1 2 2<br>2 1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤s,t,u,v≤n≤50000</p><p>1≤e≤300000</p><p>-2<sup>31</sup>≤w≤2<sup>31</sup></p>
</div>
</div>