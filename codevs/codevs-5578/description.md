<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在广袤的正方形土地上有n条水平的河流和m条垂直的河流，发达的咸鱼家族在m*n个河流交叉点都建立了城市。然而，由于河流有单一的流向，而咸鱼们却没有发达的下体，所以只能顺流而下。两两河流之间的流向互不影响。</p><p><br></p><p>现在，咸鱼冒险家Sorey决定出发去看看这个世界，但是Sorey担心自己可能被困在某个城市而无法回归自己的家乡。于是Sorey夜观天象，搞清楚了每条河的流向，他想请你帮他判断他的旅途是否会顺利。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数T,表示数据组数(T&lt;=10)</p><p>每组数据第一行两个整数n,m,含义如上述</p><p>第二行两个整数x,y,表示Sorey的初始坐标（从一开始，x表示所在行，y表示所在列）</p><p>下一行n个数，之间用空格间隔，其中第i个表示第i条水平河流的方向，0向左，1向右</p><p>下一行m个数，之间用空格间隔，其中第i个表示第i条垂直河流的方向，0向下，1向上</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一组数据一行</p><p>如果Sorey能到达任何一座城市且不可能被困住的话，输出&quot;Yes.&quot;,否则输出&quot;No.&quot;(不含引号)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1</p><p>4 6</p><p>1 1</p><p>0 1 0 1</p><p>0 1 0 1 0 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Yes.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例如图</p><p><img src="/source/codevs/codevs-5578/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01NTc4L2h0dHA6Ly9pMS5waWltZy5jb20vMTk0OS9jNzNlOGM3YzkxMmRjMjI1LmpwZw==.jpg">    <br></p><p>对于40%的数据n,m&lt;100,T=1;</p><p>对于60%的数据n,m&lt;1000;<br></p><p>对于100%的数据2&lt;=n,m&lt;=1000000,1&lt;=x&lt;=n,1&lt;=y&lt;=m;</p>
</div>
</div>