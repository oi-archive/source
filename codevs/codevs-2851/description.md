<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>六一儿童节到了，菜菜爸爸带着菜菜来到了游乐园，菜菜可高兴坏了。这不，菜菜看到了一排卖气球的，便吵着闹着要买气球。</p>
<p>不过这些卖气球的也奇怪，他们都站成了一排，而且每个人每次都只卖一定数量的气球，多了不卖，少了也不卖。</p>
<p>菜菜爸爸已经打听好了这N个人每次卖的气球数量，忽然想考考菜菜：只能从连续的若干个人那里买气球，并且气球总数必须是质数，求最大的可行的气球总数。</p>
<p>这个问题可难住了菜菜，他找到了你，请你帮忙计算该从哪个人买到哪个人，气球总数是多少。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，一个正整数N。</p>
<p>第二行，N个正整数，第i个数表示第i个人每次卖的气球数ni。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一行，三个正整数l,r,s，分别表示买第l个人到第r个人的气球，总数为s，要求s尽可能大。在有若干个最优解的情况下，输出l最小的一组。数据保证有解。</p>

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
<p>1 3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 3 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于10%的数据，有0&lt;N&lt;=20。</p>
<p>对于100%的数据，有0&lt;N&lt;=2000，0&lt;ni&lt;=1000。</p>
</div>
</div>