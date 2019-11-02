<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    贝茜喜爱吃草,总是喜欢晚上匆匆忙忙第赶去牛棚挤奶。她被安排在一个被分割成<br>R (1 &lt;= R &lt;= 100) 行和 C (1 &lt;= C &lt;= 100) 列的草场上，草场里有绿草和岩石<br>(她不能吃岩石，所有不能进入这些区域)。贝茜从地图上开始位置C_b,R_b处开始<br>出发，沿着她可能走的最短路线一路咀嚼，直到牛棚(位置在地图中的1,1)。她可<br>以从一个田块走到周围的4个任意田块。</p>
<p>    下面的例题中，岩石表示为 ('*'), 草地表示为 ('.'), 牛棚表示为('B'), 贝茜<br>表示为 ('C' for cow) 在第5行第6列，移动的最短路线如下，移动过程表示为<br> ('m'):</p>
<p>Map Optimal Munched Route<br>1 2 3 4 5 6 &lt;-col 1 2 3 4 5 6 &lt;-col<br>1 B . . . * . 1 B m m m * .<br>2 . . * . . . 2 . . * m m m<br>3 . * * . * . 3 . * * . * m<br>4 . . * * * . 4 . . * * * m<br>5 * . . * . C 5 * . . * . m</p>
<p>    贝茜共咀嚼了9个草地方格.</p>
<p>    给出一个地图，请计算出贝茜从现在位置走到牛棚一路咀嚼的最短路线长度。<br>(牛棚里没有草给奶牛们吃)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>   * 第 1 行: 2个用空格隔开的整数 R, C</p>
<p>   * 第 2 至 R+1 行: 草场地图信息</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp;&nbsp;&nbsp; * 第 1 行: 一个整数表示贝茜从现在位置走到牛棚一路咀嚼的最短路线长度</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 6<br>B...*.<br>..*...<br>.**.*.<br>..***.<br>*..*.C</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>9</p>

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