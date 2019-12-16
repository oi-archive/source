<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>传说中，南极有一片广阔的冰原，在冰原下藏有史前文明的遗址。整个冰原被横竖划分成了很多个大小相等的方格。在这个冰原上有N个大小不等的矩形冰山，这些巨大的冰山有着和南极一样古老的历史，每个矩形冰山至少占据一个方格，且其必定完整地占据方格。冰山和冰山之间不会重叠，也不会有边或点相连。以下两种情况均是不可能出现的：</p>
<p><span style="">ACM探险队在经过多年准备之后决定在这个冰原上寻找遗址。根据他们掌握的资料，在这个冰原上一个大小为一格的深洞中，藏有一个由史前人类制作的开关。而唯一可以打开这个开关的是一个占据接近一格的可移动的小冰块。显然，在南极是不可能有这样小的独立冰块的，所以这块冰块也一定是史前文明的产物。他们在想办法把这个冰块推到洞里去，这样就可以打开一条通往冰原底部的通道，发掘史前文明的秘密。冰块的起始位置与深洞的位置均不和任何冰山相邻。</span></p>
<p><span style="">请你帮助他们以最少的推动次数将冰块推入深洞中。</span><br> 这个冰原上的冰面和冰山都是完全光滑的，轻轻的推动冰块就可以使这个冰块向前滑行，直到撞到一座冰山就在它的边上停下来。冰块可以穿过冰面上所有没有冰山的区域，也可以从两座冰山之间穿过（见下图）。冰块只能沿网格方向推动。</p>

<img src="/source/codevs/codevs-2222/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yMjIyL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NzMxNzEyOC42MjAuMDYyMzc5NDU5NTM5LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行为冰山的个数N ，第二行为冰块开始所在的方格坐标X<sub>1</sub>,Y<sub>1</sub>，第三行为深洞所在的方格坐标X<sub>2</sub>,Y<sub>2</sub>，以下N行每行有四个数，分别是每个冰山所占的格子左上角和右下角坐标X<sub>i1</sub>,Y<sub>i1</sub>,X<sub>i2</sub>,Y<sub>i2</sub></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件仅包含一个整数，为最少推动冰块的次数。如果无法将冰块推入深洞中，则输出0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p>1 1</p>
<p>5 5</p>
<p>1 3 3 3</p>
<p>6 2 8 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=N&lt;=4000</p>
</div>
</div>