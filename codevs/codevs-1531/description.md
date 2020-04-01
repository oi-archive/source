<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Rocky山脉有n个山峰，一字排开，从西向东依次编号为1, 2, 3, ……, n。每个山峰的高度都是不一样的。编号为i的山峰高度为hi。</p>
<p>小修从西往东登山。每到一座山峰，她就回头观望自己走过的艰辛历程。在第i座山峰，她记录下自己回头能看到的山峰数si。</p>
<p>何谓“能看到”？如果在第i座山峰，存在j&lt;k&lt;i，hj&lt;hk，那么第j座山峰就是不可见的。除了不可见的山峰，其余的山峰都是可见的。</p>
<p>回家之后，小修把所有的si加起来得到S作为她此次旅行快乐值。现在n座山峰的高度都提供给你了，你能计算出小修的快乐值吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数n(n&lt;=15000)。</p>
<p>第i+1(1&lt;=i&lt;=n)行是一个整数hi（hi&lt;=10<sup>9</sup>）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">仅一行：快乐值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>2</p>
<p>1</p>
<p>3</p>
<p>5</p>
<p>9</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>说明：s1=0, s2=1, s3=2, s4=1, s5=1。</p>
</div>
</div>