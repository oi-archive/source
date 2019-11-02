<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       经过连续若干年的推广，Risk这个游戏已经风靡全国，成为大众喜闻乐见的重要娱乐方式。Risk这个游戏可以理解为一种简易的策略游戏，游戏者的目的是占领所有的土地。由于游戏规则的规定，只要两个国家相邻，就认为两个国家有交战的可能性。我们现在希望知道在当前的局面下，哪些国家之间有交战的可能性。注意，我们认为只有当两个国家的国界线有公共边的时候才认为相邻，若两个国家的领土只有公共点，则认为两个国家不相邻。</p>
<p>       每一个国家的边界由一系列线段组成，保证这个边界是一个简单多边形，即严格不自交。为了定位每个国家的位置，我们还给出每个国家最庞大的一支军队的位置，保证这个位置一定出现在某一个形内，而不是出现在某条边界上。</p>

<img src="/source/codevs/codevs-1370/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMzcwL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2MzkyOTk0Mi4wMC44ODI4NDc4MDUwODkuanBn.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行中包括两个整数n,m。分别表示地图上的国家数和描述国家的边界的线段的数量。1&lt;=n&lt;=600，1&lt;=m&lt;=4000。接下来n行，每行用一对数描述了某个国家的主力军队的坐标。接下来m行，每行有4个数x1,y1,x2,y2，（x1,y1）-(x2,y2)描述了一条国界线。所有点的坐标都是0-10000之间的整数。</p>
<p>保证输入的所有线段至多只会在线段交点处相交。整张地图上有且仅有一块面积无限的空白区域不属于任何国家。每一条国界线两侧的区域或者隶属于两个不同的国家，或者分隔了一个国家与那块无穷大的空白区域。即保证一条国界线两侧的区域不同时属于同一个国家或是同时都是空白区域。所有封闭区域内部包含且仅包含一支主力军队，表示了该区域的归属。</p>
<p><strong>输入说明：</strong></p>
<p>       例如上图中第一行的数据是合法的。而第二行中的数据都是不合法的。左边的那幅图包含线段两侧都是空白区域；中间的图包含线段两侧区域同时属于同一个国家；右边的图中军队被布置在了国界线上，因此非法；此外若最右侧的图中若没有军队也是非法的。保证输入文件提供的数据都是合法的，你的程序不需要进行数据合法性的判定。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp; &nbsp; &nbsp;输出文件包括n行，每行第一个数字x表示有x个国家可能与这个国家交战，接着在同一行中升序输出x个整数，表示可能与这个国家交战的国家的编号。国家按输入中给出的顺序从1到n编号。注意数字间严格以一个空格隔开，并且不要在行末输出多余的空白字符。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 12</p>
<p>3 2</p>
<p>11 8</p>
<p>12 17</p>
<p>1 19</p>
<p>0 0 10 0</p>
<p>10 0 20 0</p>
<p>20 0 20 10</p>
<p>20 10 20 20</p>
<p>20 20 10 20</p>
<p>10 20 0 20</p>
<p>0 20 0 10</p>
<p>0 10 0 0</p>
<p>10 0 10 10</p>
<p>0 10 10 10</p>
<p>20 10 10 10</p>
<p>10 20 10 10</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 2 4</p>
<p>2 1 3</p>
<p>2 2 4</p>
<p>2 1 3</p>

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