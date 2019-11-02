<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小爱整天收到花。她有N个花瓶标号从0到N-1。如果她收到F朵花，她会选择一个花瓶A，尝试去放花进去那个花瓶。如果那个花瓶已经有花，她就顺序地找下一个，直到所有花都放完或者后面没有花瓶了。有时她会清理花瓶，把花瓶A到B（A&lt;=B）之间的花全扔了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数N和M代表花瓶数和操作数。</p>
<p>然后M行每行第一个数字是K(1或2)。如果K是1，那么再输入A和F，如果K是2，那么输入A和B，含义如上所述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>每个操作输出一行。</p>
<p>对于操作1，输出成功放花的第一个位置和最后一个位置，如果一朵花都没放，输出&lsquo;Can not put any one.&rsquo;。</p>
<p>对于操作2，输出扔了多少花。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<div>
<p>10 5</p>
<p>1 3 5</p>
<p>2 4 5</p>
<p>1 1 8</p>
<p>2 3 6</p>
<p>1 8 8</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>3 7</p>
<p>2</p>
<p>1 9</p>
<p>4</p>
<p>Can not put any one.</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于40%的数据，有1≤<em>N,M</em>≤100。       对于100%的数据，有1≤<em>N,M</em>≤50000。<strong></strong></p>
</div>
</div>