<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个矩形的坑的底部，无缝地铺了一层积木（为简单起见，本题中，用矩形表示积木），如下图所示（阴影部分表示地，中空的部分表示坑，所有的白色矩形都表示坑底的积木）：</p>
<p>现在，我们要在这个坑中再放入一块正方形积木，但我们希望这块积木的位置最低。如下图所示，左图中的灰色积木的位置就比右图中灰色积木的位置更好（本题不考虑重力因素，假定新放入的积木不会倾倒，它的边永远平行于坑壁）。而且，可以看出，左图中灰色方块的位置是所有可能的位置中最低的位置（本题中，假定坑足够宽也足够深，后加的那块积木不会放不进去）。</p>
<p>如果事先给定所有事先铺好的积木的信息和后加的积木的信息，请编写程序寻找一下它的最低位置。</p>
<p> </p>

<img src="/source/codevs/codevs-1605/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNjA1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2NDg5Nzk1OC44MTAuMzU4NTc2ODIzOTkzLmJtcA==.bmp" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件第一行为一个整数 n，表示坑底积木的数量。<br> 之后n行，每行两个整数，依次表示从左至右的每块积木的宽度和高度（以厘米为单位）。<br> 最后一行中还有一个整数 ，表示后加的积木的边长（以厘米为单位）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>文件中只有一个整数，表示将后加的积木放入坑中最低位置之后，它的上沿距离坑底地面的高度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br> 10 40<br> 15 60<br> 20<br><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>80</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>