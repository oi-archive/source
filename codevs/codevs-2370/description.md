<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小机房有棵焕狗种的树，树上有N个节点，节点标号为0到N-1，有两只虫子名叫飘狗和大吉狗，分居在两个不同的节点上。有一天，他们想爬到一个节点上去搞基，但是作为两只虫子，他们不想花费太多精力。已知从某个节点爬到其父亲节点要花费 c 的能量（从父亲节点爬到此节点也相同），他们想找出一条花费精力最短的路，以使得搞基的时候精力旺盛，他们找到你要你设计一个程序来找到这条路，要求你告诉他们最少需要花费多少精力</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<pre>第一行一个n，接下来n-1行每一行有三个整数u，v, c 。表示节点 u 爬到节点 v 需要花费 c 的精力。<br>第n+1行有一个整数m表示有m次询问。接下来m行每一行有两个整数 u ，v 表示两只虫子所在的节点</pre>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一共有m行，每一行一个整数，表示对于该次询问所得出的最短距离。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 0 1</p>
<p>2 0 1</p>
<p>3</p>
<p>1 0</p>
<p>2 0</p>
<p>1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>
<p>1</p>
<p>2</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=50000， 1&lt;=m&lt;=75000， 0&lt;=c&lt;=1000</p>
</div>
</div>