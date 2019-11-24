<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>大家都知道，sheep有两只可爱的宠物（一只叫神牛，一只叫神菜）。有一天，sheep带着两只宠物到狗狗家时，这两只可爱的宠物竟然迷路了……</p>
<p>狗狗的家因为常常遭到猫猫的攻击，所以不得不把家里前院的路修得非常复杂。狗狗家前院有N个连通的分叉结点，且只有N-1条路连接这N个节点，节点的编号是1-N（1为根节点）。sheep的宠物非常笨，他们只会向前走，不会退后（只向双亲节点走），sheep想知道他们最早什么时候会相遇（即步数最少）。</p>

<img src="/source/codevs/codevs-1503/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNTAzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NDU0ODY1OS4wNjAuMDM5NDgxNzAwNDM1Ny5qcGc=.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行：一个正整数N，表示节点个数。</p>
<p>第2~N行：两个非负整数A和B，表示A是B的双亲。（保证A,B&lt;=n）</p>
<p>第N+1行：两个非负整数A和B，表示两只宠物所在节点的位置。（保证A,B&lt;=n）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出他们最早相遇的节点号。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>10<br>1 2<br>1 3<br>1 4<br>2 5<br>2 6<br>3 7<br>4 8<br>4 9<br>4 10<br>3 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于10%的数据，n&lt;10^6</p>
<p>对于100%的数据，n&lt;=10^6</p>
</div>
</div>