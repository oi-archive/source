<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    相传在一个古老的阿拉伯国家里，有一座宫殿。宫殿里有个四四方方的各自迷宫，国王选择驸马的方法非常特殊，也非常简单：公主站在其中一个方格子上，只要谁能用地毯将除公主站立的地方意外的所有地方盖上，美丽漂亮聪慧的公主就是他的人了。公主这一方格不能用地毯盖住，毯子的形状有所规定，只能有<span style="font-family: 'Times New Roman';">4</span><span style="">种选择，如下图所示：</span></p>
<p> </p>
<p>    并且每一方格只能用一层地毯，迷宫的大小为（<span style="font-family: 'Times New Roman';">2^k</span><span style="">）</span><span style="font-family: 'Times New Roman';">^2</span><span style="">的方形。当然，也不能让公主无限制地在那儿等，所以实现时限为</span><span style="font-family: 'Times New Roman';">1s</span><span style="">。</span></p>
<p> </p>

<img src="/source/codevs/codevs-1496/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNDk2L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xNDk2LmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入文件共<span>2</span><span>行。第一行：</span><span>k</span><span>，即给定被填补迷宫的大小为</span><span>2^k</span><span>（</span><span>0&lt;k&lt;=10</span><span>）；第二行：</span><span>x y</span><span>，即给出公主所在方格的坐标（</span><span>x</span><span>为行坐标，</span><span>y</span><span>为列坐标），</span><span>x</span><span>和</span><span>y</span><span>之间有一个空格隔开。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 10px;">&nbsp; &nbsp; 输出文件包括将地毯填补完整的方案，每一补</span><span style="font-size: 10px;">(</span><span style="font-size: 10px;">行</span><span style="font-size: 10px;">)</span><span style="font-size: 10px;">为</span><span style="font-size: 10px;">x&nbsp;&nbsp;y&nbsp;&nbsp;c</span><span style="font-size: 10px;">（</span><span style="font-size: 10px;">x,y</span><span style="font-size: 10px;">为毯子拐角的行坐标和列坐标，</span><span style="font-size: 10px;">c</span><span style="font-size: 10px;">为使用毯子的形状，具体见上面的图，毯子形状分别用</span><span style="font-size: 10px;">1</span><span style="font-size: 10px;">、</span><span style="font-size: 10px;">2</span><span style="font-size: 10px;">、</span><span style="font-size: 10px;">3</span><span style="font-size: 10px;">、</span><span style="font-size: 10px;">4</span><span style="font-size: 10px;">表示，</span><span style="font-size: 10px;">x</span><span style="font-size: 10px;">、</span><span style="font-size: 10px;">y</span><span style="font-size: 10px;">、</span><span style="font-size: 10px;">c</span><span style="font-size: 10px;">之间用一个空格隔开）。</span></p>
<div><span><br /></span></div>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>3  3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5  5  1</p>
<p>2  2  4</p>
<p>1  1  4</p>
<p>1  4  3</p>
<p>4  1  2</p>
<p>4  4  1</p>
<p>2  7  3</p>
<p>1  5  4</p>
<p>1  8  3</p>
<p>3  6  3</p>
<p>4  8  1</p>
<p>7  2  2</p>
<p>5  1  4</p>
<p>6  3  2</p>
<p>8  1  2</p>
<p>8  4  1</p>
<p>7  7  1</p>
<p>6  6  1</p>
<p>5  8  3</p>
<p>8  5  2</p>
<p>8  8  1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
如描述
</div>
</div>