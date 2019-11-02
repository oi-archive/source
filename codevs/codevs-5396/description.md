<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">       QZJ是一位有名的建筑师。他买了一块地来建造房子。不幸的是，这块地的地势是会变化的，它有一个可变仰角。<br>       土地的形状是一个长方形，N米宽M米长。它可以被分为N*M个方块（见下图）。QZJ的房子也是一个长方形，房子的边与土地的边都是平行的。为了房子不会倒塌，QZJ建房子的土地必须都是同一个地势的。</p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><img height="155" src="/source/codevs/codevs-5396/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01Mzk2L2h0dHA6Ly93d3cueXV5YW9pLmNuOjgwOC91cGxvYWQvMjAxNjA4LzEoMykucG5n.png" style="" width="120"></p><p style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">      上图中QZJ建立房子的其中两种是红色和蓝色覆盖的区域。计算QZJ可以有多少种方式来建立他的房子。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">输入第一行包括两个整数N和M（1≤N，M≤1000）。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">接下来的N行中每行包括M个整数ai,j（1≤ai,j≤109），表示每一块土地的地势高度。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">注意：由于输入的数据比较大，请使用更快的输入方式。（例如，C++中使用scanf而不是cin）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: &#39;Helvetica Neue&#39;, Helvetica, Arial, sans-serif; font-size: 13px; line-height: 18px; background-color: rgb(228, 240, 248);">输出一个整数，表示Bob最多有多少种建立房子的方式。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3</p><p>2 2 2</p><p>2 2 1</p><p>1 1 1</p><p>2 1 2</p><p>1 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>27</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">【数据范围】</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">20%的测试数据中，N，M≤50。</span><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;">60%的测试数据中，N，M≤500。</span></p>
</div>
</div>