<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       NBA每年都有球员选秀环节。通常用速度和身高两项数据来衡量一个篮球运动员的基本素质。假如一支球队里速度最慢的球员速度为minV，身高最矮的球员高度为minH，那么这支球队的所有队员都应该满足:</p>
<p> </p>
<p>A * ( height – minH ) + B * ( speed – minV ) &lt;= C</p>
<p> </p>
<p>其中A和B，C为给定的经验值。这个式子很容易理解，如果一个球队的球员速度和身高差距太大，会造成配合的不协调。</p>
<p> </p>
<p>请问作为球队管理层的你，在N名选秀球员中，最多能有多少名符合条件的候选球员。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行四个数N、A、B、C</p>
<p>下接N行每行两个数描述一个球员的height和speed</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>最多候选球员数目。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre><span>4 1 2 10</span></pre>
<pre><span>5 1</span></pre>
<pre><span>3 2</span></pre>
<pre><span>2 3</span></pre>
<pre><span>2 1</span></pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre><span>4</span></pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N &lt;= 5000 ,height和speed不大于10000。A、B、C在长整型以内。</p>
</div>
</div>