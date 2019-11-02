<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在平面上有N个点，M条边。</p><p>求1号点到各个点的最短距离。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，N,M。</p><p>接下来M行，每行格式形如&lt;start&gt;&lt;end&gt;&lt;v&gt;&lt;i&gt;.</p><p>表示从start到end有一条边，长度为v.</p><p>若i==0，表示这是一条有向边，只能从start走到end.</p><p>若i==1,表示这是一条无向边，可双向通行。</p><p>1&lt;=start,end&lt;=N.<br></p><p>v&gt;=0.</p><p>i=0或1.</p><p>start,end,v,i均为整数。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>N-1个数，用空格隔开。</p><p>第i个数表示1到(i+1)的最短距离.</p><p>若无法到达输出99999999</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 8</p><p>1 3 1 0</p><p>3 4 1 0</p><p>1 4 3 1</p><p>2 4 2 1</p><p>1 2 1 0</p><p>2 5 3 0</p><p>5 2 5 0</p><p>4 5 6 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 1 2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N&lt;=100</p><p>可能有重边和自环</p>
</div>
</div>