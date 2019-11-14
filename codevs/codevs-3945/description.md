<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">小Q</span><span style=""></span><span style="">获得了一个神奇的印章，这个印章宽n</span><span style=""></span><span style="">个单位长度，印章的其中三个棱都是直的，而另外一个方向上，对于每个单位宽度的部分，是一样直的，并且与反方向的棱平行，如下图所示。</span></p><p style=""><span style="">小Q</span><span style=""></span><span style="">的印章上有一个<strong><em><span style="TEXT-DECORATION: underline;">不关于中心对称</span></em></strong>的图形（不一定是上图的Qrz</span><span style=""></span><span style="">），他现在要在一张地图上拓上印，地图上有一段</span><span style=""></span><span style="">个m单位长度、近似水平的边界线，但是放大到单位长度时还是有一定的高低差异，但对于单位宽度的部分，是一样直的，与水平轴线垂直，如下图所示。</span></p><p style=""><span style=""></span></p><p style=""><span style="">小Q</span><span style="">希望自己的印章<strong><em><span style="TEXT-DECORATION: underline;">一边的边缘能恰好地与边界线重合</span></em></strong>（不能部分重合、不能越过边界线），他现在只可以<strong><em><span style="TEXT-DECORATION: underline;">将印章旋转180</span></em></strong></span><span style=""></span><strong><em><span style="TEXT-DECORATION: underline;"><span style="">度或者不旋转</span></span></em></strong><span style="">（这样印章可能存在有两边可以与边界线重合的情况），然后平移到适当的位置，问小Q</span><span style=""></span><span style="">有多少种可行的方案，两种方案不同被定义为两种方案用印章印出的图案互不重合。</span></p><p><br></p>

<img src="/source/codevs/codevs-3945/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0zOTQ1L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8zOTQ1LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行两个正整数n</span><span style=""></span><span style="">和m</span><span style=""></span><span style="">，表示印章的宽度和截取边界线的长度。</span></p><p style=""><span style="">第二行n</span><span style=""></span><span style="">个正整数，表示印章从左到右每个单位宽度对应的两条平行线之间的距离。</span></p><p style=""><span style="">第三行m</span><span style=""></span><span style="">个整数，表示所截取边界线从左到右每个单位宽度对应的竖直方向上的坐标。</span></p><p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="TEXT-INDENT: 28px"><span style="FONT-FAMILY: 宋体"></span></p><p style="TEXT-INDENT: 28px"><span style="FONT-FAMILY: 宋体">一个整数，表示可行方案的种类数。</span></p><p style="TEXT-INDENT: 28px"><span style="FONT-FAMILY: 宋体"></span></p><p>&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">5 12</span></p><p style=""><span style="">3 4 4 3 2</span></p><p style=""><span style="">2 4 5 5 4 3 2 2 3 3 2 1</span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">3</span></p><p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">对于30%</span><span style=""></span><span style="">的数据，有n*m≤2*10<sup>7</sup></span><span style=""></span><span style="">。</span></p><p style=""><span style="">对于60%</span><span style=""></span><span style="">的数据，有n，m<span style="">≤10<sup>5</sup></span></span><span style=""></span><span style="">。</span></p><p style=""><span style="">对于100%</span><span style=""></span><span style="">的数据，有n,m<span style="">≤</span>10<sup>6</sup></span><span style="">，所有数字的绝对值不超过10<sup>9</sup></span><span style=""></span><span style="">。</span></p><p> </p>
</div>
</div>