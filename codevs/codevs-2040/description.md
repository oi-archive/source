<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在商店中，每一种商品都有一个价格（用整数表示）。例如,一朵花的价格是 2 zorkmids （z），而一个花瓶的价格是 5z 。为了吸引更多的顾客，商店举行了促销活动。</p>
<p>促销活动把一个或多个商品组合起来降价销售，例如：</p>
<p>三朵花的价格是 5z 而不是 6z， 两个花瓶和一朵花的价格是 10z 而不是 12z。 编写一个程序，计算顾客购买一定商品的花费，尽量利用优惠使花费最少。尽管有时候添加其他商品可以获得更少的花费，但是你不能这么做。</p>
<p>对于上面的商品信息，购买三朵花和两个花瓶的最少花费的方案是：以优惠价购买两个花瓶和一朵花（10z），以原价购买两朵花（4z）。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件包括一些商店提供的优惠信息，接着是购物清单。（最多有5种商品）</p>
<p>第一行 优惠方案的种类数（0 &lt;= s &lt;= 99）。</p>
<p>第二行..第s+1 行 每一行都用几个整数来表示一种优惠方式。第一个整数 n （1 &lt;= n &lt;= 5），表示这种优惠方式由 n 种商品组成。后面 n 对整数 c 和 k 表示 k （1 &lt;= k &lt;= 5）个编号为 c （1 &lt;= c &lt;= 999）的商品共同构成这种优惠，最后的整数 p 表示这种优惠的优惠价（1 &lt;= p &lt;= 9999）。优惠价总是比原价低。</p>
<p>第 s+2 行 这一行有一个整数 b （0 &lt;= b &lt;= 5），表示需要购买 b 种不同的商品。</p>
<p>第 s+3 行..第 s+b+2 行 这 b 行中的每一行包括三个整数：c ，k ，和 p 。 C 表示唯一的商品编号（1 &lt;= c &lt;= 999），k 表示需要购买的 c 商品的数量（1 &lt;= k &lt;= 5）。p 表示 c 商品的原价（1 &lt;= p &lt;= 999）。最多购买 5*5=25 个商品。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>只有一行，输出一个整数：购买这些物品的最低价格。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>2
1 7 3 5
2 7 1 8 2 10
2
7 3 2
8 2 5</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>14</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>