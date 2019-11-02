<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">在一种"麻将"游戏中，游戏是在一个有W＊H格子的矩形平板上进行的。每个格子可以放置一个麻将牌，也可以不放（如图所示）。玩家的目标是将平板上的所有可通过一条路径相连的两张相同的麻将牌，从平板上移去。最后如果能将所有牌移出平板，则算过关。</span><br style=""><span style="">　　这个游戏中的一个关键问题是：两张牌之间是否可以被一条路径所连接，该路径满足以下两个特性：</span><br style=""><span style="">　　1. 它由若干条线段组成，每条线段要么是水平方向，要么是垂直方向。 </span><br style=""><span style="">　　2. 这条路径不能横穿任何一个麻将牌 (但允许路径暂时离开平板)。</span><br style=""><span style="">　　这是一个例子：</span><img src="/source/codevs/codevs-5493/img/aHR0cDovL3d3dy5oenhqaHMuY29tOjgzL2ltYWdlcy9wcm9ibGVtLzE2NTAvMS5KUEc=.JPG"></p><p><span style="">　在（1，3）的牌和在(4, 4)的牌可以被连接。(2, 3)和(3, 4)不能被连接。</span><br style=""><span style="">　　你的任务是编一个程序，检测两张牌是否能被一条符合以上规定的路径所连接。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件的第一行有两个整数n，m （1&lt;=n，m&lt;=75），表示平板的宽和高。</span><span style="">接下来m行描述平板信息，每行包含n个字符(不要弄反)</span><span style="">，如果某格子有一张牌，则这个格子上有个'X'，否则是一个空格。</span></p><p><span style="">平板上最左上角格子的坐标为（1，1），最右下角格子的坐标为（w,h）。接下来的若干行，每行有四个数x1， y1， x2， y2 ，且满足1&lt;=x1,x2&lt;=w，1&lt;=y1,y2&lt;=h，表示两张牌的坐标（这两张牌的坐标总是不同的）。如果出现连续四个0，则表示输入结束。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: 微软雅黑; font-size: 18px; line-height: 25.7143px; background-color: rgb(255, 255, 255);">输出文件中，对于每一对牌输出占一行，为连接这一对牌的路径最少包含的线段数。如果不存在路径则输出0。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 4<br></p><p>XXXXX<br></p><p>X   X<br></p><p>XXX X<br></p><p>XXX <br></p><p>2 3 5 3</p><p>1 3 4 4<br></p><p>2 3 3 4</p><p>0 0 0 0 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p><p>3</p><p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">1&lt;=w，h&lt;=75</span></p><p><span style="">每组询问中，1&lt;=x1,x2&lt;=w，1&lt;=y1,y2&lt;=h</span></p><p><span style=""></span></p><p>来自学军OJNOIP16普及模拟训练6第三题</p><p><span style=""></span><br></p>
</div>
</div>