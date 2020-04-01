<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小J有一把尺子。一天MPS闲得无聊，拿了一桶油漆，用刷子在上面刷了N下，刷第i次有一个正整数范围(ai，bi)，表示从尺子的刻度ai刷到刻度bi。此时ai到bi这个区间里的油漆层数+1。</p>
<p>为了去掉这些油漆，小J找来了一把刀，每次可以从尺子的一个整数刻度刮到另一个整数刻度。每刮一刀都有一个力度，如力度为3时可以一次刮掉3层油漆。但不能损坏尺子。比如有2层油漆的地方就不能用力度3来刮。</p>
<p>小J想知道最少要刮多少次。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个整数N</p>
<p>第2...N+1行，第i+1行两个整数ai，bi。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行，最少刮多少次。</p>

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
<p>1 4</p>
<p>2 5</p>
<p>1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】</p>
<p>刮2刀，第一次刮区间(1,5)，力度为2，第一次刮区间(2,4)，力度为1。</p>
<p>【数据范围】</p>
<p>40%的数据N&lt;=2000</p>
<p>100%的数据N,ai,bi&lt;=10^5</p>
</div>
</div>