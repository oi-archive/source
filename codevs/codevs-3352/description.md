<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一棵树，树上有只毛毛虫。它在这棵树上生活了很久，对它的构造了如指掌。所以它在树上从来都是走最短路，不会绕路。它还还特别喜欢三角形，所以当它在树上爬来爬去的时候总会在想，如果把刚才爬过的那几根树枝/树干锯下来，能不能从中选三根出来拼成一个三角形呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含一个整数 N，表示树上节点的个数（从 1 到 N 标号）。</p>
<p>接下来的 N-1 行包含三个整数 a, b, len，表示有一根长度为 len 的树枝/树干在节点 a 和节点 b 之间。</p>
<p>接下来一行包含一个整数 M，表示询问数。</p>
<p>接下来M行每行两个整数 S, T，表示毛毛虫从 S 爬行到了 T，询问这段路程中的树枝/树干是否能拼成三角形。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>接下来对于每个询问输出一行，包含"Yes"或&ldquo;No&rdquo;，表示是否可以拼成三角形。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>5</pre>
<pre>1 2 5</pre>
<pre>1 3 20</pre>
<pre>2 4 30</pre>
<pre>4 5 15</pre>
<pre>2</pre>
<pre>3 4</pre>
<pre>3 5</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>NO</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>10%的数据中N&lt;=1000<br> M&lt;=1000<br> 30%的数据树是随机构造的<br> 100%的数据中N&lt;=100000<br> M&lt;=100000</p>
<p>边权小于10^9</p>
</div>
</div>