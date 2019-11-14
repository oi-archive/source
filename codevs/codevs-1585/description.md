<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""> </p>
<p><!--EndFragment-->有下面这样的一个网格棋盘，a，b，c，d表示了对应边长度，也就是对应格子数。</p>
<p> </p>
<p>当a=b=c=d=2时，对应下面这样一个棋盘（如下图所示）。要在这个棋盘上放k个相互不攻击的车，也就是这k个车没有两个车在同一行，也没有两个车在同一列，问有多少种方案。同样只需要输出答案mod 100003后的结果。</p>
<p> </p>

<img src="/source/codevs/codevs-1585/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNTg1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTU4NV8xLnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件place.in的第1行为有5个非负整数a, b, c, d和k。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件place.out包括1个正整数，为答案mod 100003后的结果。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2 2 2 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>38</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于部分数据，有b = 0；</p>
<p>对于部分数据，有a,b,c,d≤4。</p>
<p>对于100%的数据，a,b,c,d,k≤1000，且保证了至少有一种可行方案。</p>
</div>
</div>