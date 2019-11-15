<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>智能车比赛<br>【问题描述】<br>新一届智能车大赛在JL大学开始啦！比赛赛道可以看作是由n个矩形区域拼接而成（如下图所示），每个矩形的边都平行于坐标轴，第i个矩形区域的左下角和右上角坐标分别为(xi,1,yi,1)和(xi,2,yi,2)。 题目保证：xi,1&lt;xi,2=xi+1,1，且yi,1&lt; yi,2，相邻两个矩形一定有重叠在一起的边（如图中虚线所示），智能车可以通过这部分穿梭于矩形区域之间。<br>选手们需要在最快的时间内让自己设计的智能车从一个给定的起点S点到达一个给定的终点T点，且智能车不能跑出赛道。假定智能车的速度恒为v且转向不消耗任何时间，你能算出最快需要多少时间完成比赛么？</p>

<img src="/source/codevs/codevs-1123/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMTIzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTEyMy5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>从文件car.in中读入数据。 输入的第一行包含一个正整数n，表示组成赛道的矩形个数。 接下来n行描述这些矩形，其中第i行包含4个整数xi,1, yi,1, xi,2, yi,2，表示第i个矩形左下角和右上角坐标分别为(xi,1, yi,1)和(xi,2, yi,2)。 接下来一行包含两个整数xS, yS，表示起点坐标。 接下来一行包含两个整数xT, yT，表示终点坐标。 接下来一行包含一个实数v(1≤v≤10 )，表示智能车的速度。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出到文件car.out中。 仅输出一个实数，至少精确到小数点后第六位，为智能车完成比赛的最快时间。</p>

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
<p>1 1 2 2</p>
<p>2 0 3 4</p>
<p>1 1</p>
<p>30</p>
<p>1.0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2.41421356</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n&lt;=2000</p>
<p>所有坐标均为整数 且绝对值不超过 40000</p>
</div>
</div>