<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Freda要到Rainbow的城堡去玩了。我们可以认为两座城堡位于同一条数轴上，Freda的城堡坐标是0，Rainbow的城堡坐标是N。正常情况 下，Freda会朝着同一个方向（即Rainbow的城堡相对于Freda的城堡的方向）走若干步之后来到Rainbow的城堡，而且步长都为1或2。可 是，今天Freda在途中遇见了来自上海的小猫Resodo，惊奇之下，居然有一步走反了方向！不过，Freda并没有神智不清，它只有一步走反了方向， 而且这一步的步长也是1或2. 同时，Freda并不会路过Rainbow的城堡而不停下来。当然，Freda是在途中遇到Resodo的，所以它不会在 自己家门口就走错方向。<br> 举个例子，如果Rainbow的城堡坐标是3，那么下面两条路径是合法的：<br> 0-&gt;1-&gt;2-&gt;1-&gt;3<br> 0-&gt;1-&gt;-1-&gt;1-&gt;3<br> 当然，还有其它的合法路径。下面这些路径则是不合法的：<br> 0-&gt;-1-&gt;1-&gt;3 （Freda不可能第一步就走错方向）<br> 0-&gt;1-&gt;3（Freda一定是有一步走错方向的）<br> 0-&gt;2-&gt;1-&gt;0-&gt;2-&gt;3（Freda只有一步是走错方向的）<br> 0-&gt;-1-&gt;0-&gt;3（Freda每步的长度一定是1或2）<br> 0-&gt;1-&gt;2-&gt;4-&gt;3（Freda不会越过Rainbow的城堡再回来）<br> 0 -&gt; 1 -&gt; 2 -&gt; 3 -&gt; 2 -&gt; 3（Freda一旦到达了Rainbow的城堡，就会停下来）<br>你现在需要帮助Freda求出，它一共有多少种方法能够到达Rainbow的城堡呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行一个整数N，表示Rainbow城堡的坐标</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;一行一个整数，表示Freda到Rainbow城堡的不同路径数。由于这个数字可能很大，你只需要输出它mod&nbsp;1000000007的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>5</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> 对于第一组样例，如下5条路径是合法的：<br> 0-&gt;1-&gt;0-&gt;2<br> 0-&gt;1-&gt;-1-&gt;0-&gt;1-&gt;2<br> 0-&gt;1-&gt;-1-&gt;0-&gt;2<br> 0-&gt;1-&gt;0-&gt;1-&gt;2<br> 0-&gt;1-&gt;-1-&gt;1-&gt;2</p>
<p> </p>
<p>数据范围与约定<br>    对于10%的数据，N&lt;=20.<br>    对于70%的数据，N&lt;=1000.<br>    对于90%的数据，N&lt;=1000000.<br>    对于100%的数据，N&lt;=10^15.</p>
</div>
</div>