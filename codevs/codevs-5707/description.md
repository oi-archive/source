<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>YHZ大神听一位<strong>艺术家</strong>说在水池里刷题可以收获更多，就让WYB在他家<strong>正方形</strong>的后花园里面建了许多小水池。但YHZ想要更大的水池，于是把<strong>部分</strong>相邻水池间凿开，变成更大的水池。但因为YHZ忙于刷题，不想计算有多少个水池，就请你帮帮忙。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行n，m，表示水池的长和宽。</p><p>第二行h，表示YHZ的身高。</p><p>接下来输入水池的深度。</p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行ans，水池的数量</p><p>第二行，如果YHZ可以在水池里刷题，<strong>即mapmax&lt;h（严格小于）</strong>，输出YES，反之，输出NO</p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4<br></p><p>10</p><p>1000</p><p>0972</p><p>0501</p><p>0020</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br></p><p>YES</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>60%数据保证1&lt;=m&lt;=20，1&lt;=n&lt;=20</p><p>100%数据保证1&lt;=m&lt;=100，1&lt;=n&lt;=100，<strong>m=n</strong>，1&lt;=h&lt;=100，<strong>0&lt;=map[i,j]&lt;10</strong>，ans&lt;=100</p><p><strong>算法提示：dfs/bfs</strong></p><p><span style=""><strong><span style="">p.s.<span style="font-family: 'comic sans ms';">如果没有水池，YHZ就不能愉快的刷题了!!!</span></span></strong></span><span style=""><strong><span style="text-decoration: line-through; font-family: 'comic sans ms';">(此时输出NO)</span></strong></span><br></p><p><span style="">数据已加强</span></p>
</div>
</div>