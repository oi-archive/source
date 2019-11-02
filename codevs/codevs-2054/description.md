<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>母牛们不但创建了它们自己的政府而且选择了建立了自己的货币系统。由于它们特殊的思考方式，它们对货币的数值感到好奇。</p>
<p>传统地，一个货币系统是由1,5,10,20 或 25,50, 和 100的单位面值组成的。</p>
<p>母牛想知道有多少种不同的方法来用货币系统中的货币来构造一个确定的数值。</p>
<p>举例来说, 使用一个货币系统 {1,2,5,10,...}产生 18单位面值的一些可能的方法是:18x1, 9x2, 8x2+2x1, 3x5+2+1,等等其它。 写一个程序来计算有多少种方法用给定的货币系统来构造一定数量的面值。保证总数将会适合long long (C/C++) 和 Int64 (Free Pascal)，即在0 到2^63-1之间。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>货币系统中货币的种类数目是 V (1&lt;=V&lt;=25)。要构造的数量钱是 N (1&lt;= N&lt;=10,000)。</p>
<p>第一行: 二个整数，V 和 N 。</p>
<p>第二行： 可用的货币的面值 。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>单独的一行包含那个可能的用这v种硬币凑足n单位货币的方案数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>3 10
1 2 5</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>10</p>

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