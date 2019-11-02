<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>邪教喜欢在各种各样空间内跳。</p>
<p>现在，邪教来到了一个二维平面。在这个平面内，如果邪教当前跳到了(x,y)，那么他下一步可以选择跳到以下4个点：(x-1,y), (x+1,y), (x,y-1), (x,y+1)。</p>
<p>而每当邪教到达一个点，他需要耗费一些体力，假设到达(x,y)需要耗费的体力用C(x,y)表示。</p>
<p>对于C(x,y)，有以下几个性质：</p>
<p>1、若x=0或者y=0，则C(x,y)=1。</p>
<p>2、若x&gt;0且y&gt;0，则C(x,y)=C(x,y-1)+C(x-1,y)。</p>
<p>3、若x&lt;0且y&lt;0，则C(x,y)=无穷大。</p>
<p>现在，邪教想知道从(0,0)出发到(N,M)，最少花费多少体力（到达(0,0)点花费的体力也需要被算入）。</p>
<p>由于答案可能很大，只需要输出答案对10^9+7取模的结果。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>读入两个整数N，M，表示邪教想到达的点。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="NOI">输出仅一个整数，表示邪教需要花费的最小体力对10^9+7取模的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于10%的数据，满足N, M&lt;=20；</p>
<p>对于30%的数据，满足N, M&lt;=100；</p>
<p>对于60%的数据，满足min(N,M)&lt;=100；</p>
<p>对于100%的数据，满足0&lt;=N, M&lt;=10^12，N*M&lt;=10^12。</p>
</div>
</div>