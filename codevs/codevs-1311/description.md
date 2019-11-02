<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span> 小白家门前有一颗小白树，树上的每个节点u都有一个权值W(u)。</span><br><span>  小白树的奇特之处在于树上有两个不同的中心点x和y。</span><br><span>  这两个中心点满足F(x,y)=ΣMin(Dis(u,x),Dis(u,y))*W(u)最小，其中Dis表示两个节点的距离。</span><br><span>  通俗地讲，就是对于每个节点u，求出G(u)表示它到x的距离和到y的距离中间小的那个乘以它的权值。</span><br><span>  那么所有G(u)的和就是F(x,y)。</span><br><span>  现在小白想让你找出这两个中心点。你只需要输出F(x,y)就可以了。</span><br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行有一个整数N(2&lt;=N&lt;=500000)N表示小白树的节点个数。</span><br><span>  之后N-1行每行有两个整数a和b表示a和b之间有一条边。</span><br><span>  之后N行每行有一个整数，第i个整数表示W(i)(0&lt;=W&lt;=10000)。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; 一个整数表示F(x,y)。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>  5<br>  1 2<br>  1 3<br>  3 4<br>  3 5<br>  5<br>  7<br>  6<br>  5<br>  4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>  14</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>