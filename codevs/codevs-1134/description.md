<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>为了准备一个独特的颁奖典礼，组织者在会场的一片矩形区域（可看做是平面直角坐标系的第一象限）铺上一些矩形地毯。一共有n 张地毯，编号从1 到n。现在将这些地毯按照编号从小到大的顺序平行于坐标轴先后铺设，后铺的地毯覆盖在前面已经铺好的地毯之上。地毯铺设完成后，组织者想知道覆盖地面某个点的最上面的那张地毯的编号。注意：在矩形地毯边界和四个顶点上的点也算被地毯覆盖。</p>

<img src="/source/codevs/codevs-1134/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMTM0L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMTM0LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入共 n+2 行。<br>第一行，一个整数 n，表示总共有n 张地毯。<br>接下来的 n 行中，第i+1 行表示编号i 的地毯的信息，包含四个正整数a，b，g，k，每两个整数之间用一个空格隔开，分别表示铺设地毯的左下角的坐标（a，b）以及地毯在x轴和y 轴方向的长度。<br>第 n+2 行包含两个正整数x 和y，表示所求的地面的点的坐标（x，y）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出共 1 行，一个整数，表示所求的地毯的编号；若此处没有被地毯覆盖则输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>3<br>1 0 2 3<br>0 2 3 3<br>2 1 3 3<br>2 2</p>
<p> </p>
<p>样例2：</p>
<p>3 <br>1 0 2 3 <br>0 2 3 3 <br>2 1 3 3 <br>4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>3</p>
<p> </p>
<p>样例2：</p>
<p>-1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围<br>对于 30%的数据，有n≤2；<br>对于 50%的数据，0≤a, b, g, k≤100；<br>对于 100%的数据，有0≤n≤10,000，0≤a, b, g, k≤100,000。</p>
</div>
</div>