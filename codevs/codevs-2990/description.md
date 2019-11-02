<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>约翰先生获得了一大笔遗产，他暂时还用不上这一笔钱，他决定进行投资以获得更大的效益。银行工作人员向他提供了多种债券，每一种债券都能在固定的投资后，提供稳定的年利息。当然，每一种债券的投资额是不同的，一般来说，投资越大，收益也越大，而且，每一年还可以根据资金总额的增加，更换收益更大的债券。</p>
<p>例如：有如下两种不同的债券：①投资额$4000，年利息$400；②投资额$3000，年利息$250。初始时，有$10000的总资产，可以投资两份债券①债券，一年获得$800的利息；而投资一份债券①和两份债券②，一年可获得$900的利息，两年后，可获得$1800的利息；而所有的资产达到$11800，然后将卖掉一份债券②，换购债券①，年利息可达到$1050；第三年后，总资产达到$12850，可以购买三份债券①，年利息可达到$1200，第四年后，总资产可达到$14050。</p>
<p>现给定若干种债券、最初的总资产，帮助约翰先生计算，经过n年的投资，总资产的最大值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为三个正整数s,n,d，分别表示最初的总资产、年数和债券的种类。</p>
<p>接下来d行，每行表示一种债券，两个正整数a,b分别表示债券的投资额和年利息。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">仅一个整数，表示n年后的最大总资产。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10000 4 2</p>
<p>4000 400</p>
<p>3000 250</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14050</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据规模：</p>
<p>s≤106，n≤40，d≤10，a≤104,且a是1000的倍数，b不超过a的10%。</p>
<p>多重背包，最大值不超过46,000,000。</p>
</div>
</div>