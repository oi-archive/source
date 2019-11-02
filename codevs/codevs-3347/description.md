<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>许多国王都碰到了经济问题。许多年来，他们都通过秘密渠道互相借钱，但是当他们的债务曝光的时候，崩溃是不可避免的。</p>
<p>现在有许多对国王，我们认为每一对国王(a,b)中a欠B的欠款用Dab来表示（我们定义Dab=-Dba）。当一个国王的经济问题入不敷出（收入小于支出），那么它就破产了，它所有的债务问题，不管是他借别人的，还是别人借他的都会一笔勾销。然后资金链断裂后，下一个国王也会破产，直到剩下的国王他们的收入还是大于支出的。</p>
<p><strong>每一时刻只能有一个国王破产</strong>，根据谁<strong>第一个破产</strong>，这个破产的结果可能有很多种，甚至很多时候只剩下一个国王。让你写出一个程序找出所有能成为唯一的不破产者的国王。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行N表示有N个国王。（n&lt;=20）</p>
<p>下面一个N*N的矩阵D。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果没有一个国王能成为最后唯一的不破产者，输出0。</p>
<p>否则顺序输出国王编号。</p>

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
<p>0 -3 1</p>
<p>3 0 -2</p>
<p>-1 2 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>30%数据保证n&lt;=5。</p>
<p>100%数据保证n&lt;=20。</p>
</div>
</div>