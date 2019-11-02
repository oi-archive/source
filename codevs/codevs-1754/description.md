<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>M国是个多雨的国家，尤其是P城，频繁的降雨给人们的出行带来了不少麻烦。为了方便行人雨天过马路，有关部门在每处人行横道的上空都安装了一种名为“自动伞”的装置。（如图1所示）</p>
<p>每把自动伞都可以近似地看作一块长方形的板，厚度不计。这种伞有相当出色的吸水能力，落到上面的雨水都会完全被伞顶的小孔吸入，并通过管道运走。不下雨时，这些伞闲置着。一旦下雨，它们便立刻开始作匀速率直线往返运动：从马路的一边以固定的速率移动到另一边，再从另一边以相同的速率返回，如此往复，直到雨停为止。任何时刻自动伞都不会越过马路的边界。有了自动伞，下雨天没带伞的行人只要躲在伞下行走，就不会被雨淋着了。</p>
<p>由于自动伞的大小有限，当需要使用自动伞过马路的人比较多时，一把自动伞显然是不够的，所以有关部门在几处主要的人行横道上空安装了多把自动伞。每把自动伞的宽度都等于人行横道的宽度，高度各不相同，长度不一定相同，移动速率也不一定相同。</p>
<p>现在已知一处人行横道的详细情况，请你计算从开始下雨到<em>T</em>秒钟后的这段时间内，一共有多少体积的雨水降落到人行横道上。</p>
<p> </p>

<img src="/source/codevs/codevs-1754/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNzU0L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTc1NC5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有四个整数<em>N</em>，<em>W</em>，<em>T</em>，<em>V</em>。<em>N</em>表示自动伞的数目，<em>W</em>表示马路的宽度，<em>T</em>表示需要统计从开始下雨到多长时间后的降雨情况，<em>V</em>表示单位面积单位时间内的降雨体积。</p>
<p>为了描述方便，我们画出了一个如图2所示的天空中五把伞的剖面图，取马路左边界为原点，取向右为<em>x</em>轴正方向，取向上为y轴正方向，建立平面直角坐标系。这样，每把自动伞都可以看作平面上的一条线段。</p>
<p><span style="">接下来的</span><em style="">N</em><span style="">行，每行用三个整数描述一把自动伞。第一个数</span><em style="">x</em><span style="">是伞的初始位置，用它左端点的横坐标表示。第二个数</span><em style="">l</em><span style="">是伞的长度，即x方向上的尺寸。第三个数</span><em style="">v</em><span style="">是伞的速度，</span><em style="">v</em><span style="">的大小表示移动的速率。如果</span><em style="">v</em><span style="">&gt;0，表示开始时伞向右移动；如果</span><em style="">v</em><span style="">&lt;0，表示开始时伞向左移动；如果</span><em style="">v</em><span style="">=0，表示伞不动。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 10px;">输出文件只包含一个实数，表示从开始下雨到</span><em style="font-size: 10px;">T</em><span style="font-size: 10px;">秒钟后，一共有多少体积的水降落到人行横道上。输出结果精确到小数点后第二位。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 4 3 10</p>
<p>0 1 1</p>
<p>3 1 -1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>65.00</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p> 雨点均匀地匀速竖直下落<br> 自动伞和马路两者都是水平的<br> 自动伞的宽度和人行横道的宽度相等，都等于1<br> N≤10<br> W≤100<br> T≤100<br> V≤50<br> 所有自动伞的往返次数之和不超过250，一来一回算一个往返。</p>
</div>
</div>