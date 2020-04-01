<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>李哲非常非常喜欢柠檬树，特别是在静静的夜晚，当天空中有一弯明月温柔 地照亮地面上的景物时，他必会悠闲地坐在他亲手植下的那棵柠檬树旁，独自思 索着人生的哲理。 <br>李哲是一个喜爱思考的孩子，当他看到在月光的照射下柠檬树投在地面上的 影子是如此的清晰，马上想到了一个问题：树影的面积是多大呢？ <br>李哲知道，直接测量面积是很难的，他想用几何的方法算，因为他对这棵柠 檬树的形状了解得非常清楚，而且想好了简化的方法。 <br>李哲将整棵柠檬树分成了 n 层，由下向上依次将层编号为 1,2,…,n。从第 1 到 n-1 层，每层都是一个圆台型，第 n 层(最上面一层)是圆锥型。对于圆台型， 其上下底面都是水平的圆。对于相邻的两个圆台，上层的下底面和下层的上底面 重合。第 n 层(最上面一层)圆锥的底面就是第 n-1 层圆台的上底面。所有的底面 的圆心(包括树顶)处在同一条与地面垂直的直线上。李哲知道每一层的高度为 h1,h2,…,hn，第 1 层圆台的下底面距地面的高度为 h0，以及每层的下底面的圆的 半径 r1,r2,…,rn。李哲用熟知的方法测出了月亮的光线与地面的夹角为 alpha。</p>
<p>为了便于计算，假设月亮的光线是平行光，且地面是水平的，在计算时忽略 树干所产生的影子。李哲当然会算了，但是他希望你也来练练手。 </p>

<img src="/source/codevs/codevs-1786/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzg2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NTc3MDY2NS43NzAuMzI3NzMyNzk0NjQzLnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件的第 1 行包含一个整数 n 和一个实数 alpha，表示柠檬树的层数和月亮 的光线与地面夹角(单位为弧度)。 第 2 行包含 n+1 个实数 h0,h1,h2,…,hn，表示树离地的高度和每层的高度。 第 3 行包含 n 个实数 r1,r2,…,rn，表示柠檬树每层下底面的圆的半径。 上述输入文件中的数据，同一行相邻的两个数之间用一个空格分隔。 输入的所有实数的小数点后可能包含 1 至 10 位有效数字。 </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出 1 个实数，表示树影的面积。四舍五入保留两位小数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 <span style="">0.7853981633 </span></p>
<p><span style="">10.0 10.00 10.00</span></p>
<p><span style=""> 4.00 5.00</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>171.97</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤n≤500，0.3&lt;alpha&lt;π/2，0&lt;hi≤100，0&lt;ri≤100。</p>
<p>10%的数据中，n=1。</p>
<p>30%的数据中，n≤2。</p>
<p>60%的数据中，n≤20。</p>
<p>100%的数据中，n≤500。 </p>
</div>
</div>