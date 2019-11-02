<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>天空中有n朵云，在风吹之下以恒定速度v=(vx,vy) <span style="">向同一个方向持续移动，也就是说，当时间为</span>t（t≥0<span style="">）时，云上初始坐标为</span><span style="font-family: 'Times New Roman';">(</span>x, y)<span style="">的点移到坐标为</span><span style="font-family: 'Times New Roman';">( </span>x + t*vx, y + t*vy)<span style="">的位置。</span></p>
<p>为简单起见，我们假设云是多边形的（而且其顶点具有整数坐标）。多边形不一定是凸的，但是每个多边形的任意两条边不相交（允许具有公共的端点）。云和云可能会重叠。</p>
<p><br>地面上有一人造卫星控制中心，位于坐标<span style="font-family: 'Times New Roman';">(0,0)</span><span style="">处，在控制中心正上方的云层之上，有一颗人造卫星。一道激光束从控制中心笔直地向上射向人造卫星，这道激光束用于与卫星进行通信。然而，当激光束的光路被云遮住时，通信就会中断。最初激光束不与任何一片云相交。在观测期间，会有若干个这样的时段，在这些时段期间激光束的光路穿过一片或几片云，使得通信中断。甚至当激光束遇到云的某个顶点时，通信也会有瞬间的中断。你需要写一个程序来计算在所有云移过之前，通信会中断多少次<br>。</span></p>
<p><span style=""><br></span></p>

<img src="/source/codevs/codevs-1244/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMjQ0L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMjQ0LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行n,vx,vy分别代表云的数目和移动速度</p>
<p>接下来n行表示n朵云，先是一个整数k表示云的顶点个数，接下来2k个整数分别代表k个顺时针的顶点坐标。</p>
<p>激光束穿过云层外围最多100000次。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个整数，代表通信被中断的次数</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 -2 -1</p>
<p>4 6 2 6 4 8 4 8 2</p>
<p>4 2 3 1 -1 2 5 4 2</p>
<p>3 -3 1 -1 2 -1 -1</p>
<p>5 5 3 3 3 3 5 6 5 6 -1</p>

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
<p>1≤云的数目n≤1000</p>
<p>3≤云的边数k≤1000</p>
<p>产生的交点数目v≤100000</p>
<p>-10<sup>9</sup>≤每个点的坐标xi,yi≤10<sup>9</sup></p>
<p>-10<sup>9</sup>≤云的移动速度vx,vy≤10<sup>9</sup></p>
</div>
</div>