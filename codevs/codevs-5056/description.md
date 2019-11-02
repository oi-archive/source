<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>潜水员为了潜水要使用特殊装备。他有一个带两种气体的气缸：一个为氮气，一个为氧气。让潜水员下潜的深度需要各种数量的氧和氮。潜水员有一定数量的气缸。每个气缸都有重量和气体容量。潜水员为了完成他的工作需要特定的氧和氮。他完成工作所需气缸的总重最低限度是多少？</p><p>例如：潜水员有5个气缸。每行有三个数字为：氧、氮的量（升）和气缸的重量：</p><p>3 36 120</p><p>10 25 129</p><p>5 50 250</p><p>1 45 130</p><p>4 20 119</p><p>如果潜水员需要5升的氧和60升的氮则总重的最小值为249（1，2或4,5号气缸）。</p><p>你的任务就是计算潜水员为了完成他的工作需要的气缸的重量的最低值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有2个整数m,n(1&lt;=m&lt;=21,1&lt;=n&lt;=79)。它们表示氧、氮各自需要的量。<br></p><p>第二行为整数k(1&lt;=k&lt;=1000)表示气缸的个数。</p><p>此后的k行，每行包括ai,bi,ci(1&lt;=ai&lt;=21,1&lt;=bi&lt;=79,1&lt;=ci&lt;=800)3整数。这些各自是：第i个气缸里的氧和氮的容量及气缸重量。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，包含一个整数，为潜水员完成工作所需气缸的重量总和的最低值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 60</p><p>5</p><p>3 36 120</p><p>10 25 129</p><p>5 50 250</p><p>1 45 130</p><p>4 20 119</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>249</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=m&lt;=21,1&lt;=n&lt;=79</p><p>1&lt;=k&lt;=1000</p><p>1&lt;=ai&lt;=21,1&lt;=bi&lt;=79,1&lt;=ci&lt;=800</p>
</div>
</div>