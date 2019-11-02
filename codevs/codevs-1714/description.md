<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    对于一个给定的S={a1,a2,a3,…,an},若有P={ax1,ax2,ax3,…,axm},满足(x1&lt;x2&lt;…&lt;xm) 且（ax1&lt;ax2&lt;…&lt;axm)。那么就称P为S的一个上升序列。如果有多个P满足条件，那么我们想求字典序最小的那个。</p>
<p> </p>
<p>    给出S序列，给出若干询问。对于第i个询问，求出长度为Li的上升序列，如有多个，求出字典序最小的那个（即首先x1最小，如果不唯一，再看x2最小……），如果不存在长度为Li的上升序列，则打印Impossible.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    第一行一个N，表示序列一共有N个元素</p>
<p>    第二行N个数，为a1,a2,…,an</p>
<p>    第三行一个M，表示询问次数。下面接M行每行一个数L，表示要询问长度为L的上升序列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp; &nbsp; 对于每个询问，如果对应的序列存在，则输出，否则打印Impossible.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>3 4 1 2 3 6</p>
<p>3</p>
<p>6</p>
<p>4</p>
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Impossible</p>
<p>1 2 3 6</p>
<p>Impossible</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N&lt;=10000</p>
<p>M&lt;=1000</p>
<p> </p>
</div>
</div>