<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>背景：由于最近昂<strong><span style="text-decoration: line-through;">存档了,</span></strong><span style="text-decoration: none;">所以</span>昂决定要和蕾姆出去约会！很不幸的是，艾米莉娅交给了昂一个任务。</p><p>描述：<span style="text-decoration: line-through;">众所周知</span><span style="text-decoration: none;"> 在罗兹瓦尔家有一个很大的草坪，可以视为N*N的矩阵，矩阵被分为N*N个小格子。这个草坪有魔法气息，能够得知每个方格上的生物数量。不幸的是最近草坪上都是土拨鼠，每个格子在某个时刻可能会钻出一定数目的土拨鼠，但土拨鼠也有可能会钻回去，为了能尽快的消灭这些</span><span style="text-decoration: line-through;">萌萌的</span><span style="text-decoration: none;">土拨鼠，昂决定向你求助，他想很快地知道某个矩形区域内有几只土拨鼠。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入有多行</p><p>第一个数x代表指令：</p><p>若x=0，接下来输入一个数s，代表初始矩阵的规模，保证s只在开头出现一次</p><p>若x=1，接下来输入三个数x，y，m表示(x,y)坐标的土拨鼠钻出m只(m可以为正数也可以为负数）</p><p>若x=2，接下来输入四个数x1，y1，x2，y2，输出(x1,y1)到(x2,y2)矩形范围内土拨鼠的数量</p><p>x=3时停止，该数据只在末尾出现一次</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="white-space: normal;"><span style="text-indent: 35px; font-family: 宋体;">对于除了</span><span style="text-indent: 35px;">2</span><span style="text-indent: 35px; font-family: 宋体;">之外的提示，你的程序不应该输出任何东西。如果指示是</span><span style="text-indent: 35px;">2</span><span style="text-indent: 35px; font-family: 宋体;">，那么你的程序应该输出一个整数。</span></p><p><span style="text-indent: 35px; font-family: 宋体;">每个整数之间有换行。</span></p><p><span style="text-indent: 35px; font-family: 宋体;">保证答案不小于0。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>0 4</p><p>1 1 2 3</p><p>2 0 0 2 2</p><p>1 1 1 2</p><p>1 1 2 -1</p><p>2 1 1 2 3</p><p><span style="font-family: Times New Roman, serif;"><span style="">3</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p><p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据S&lt;=30，修改和查询次数一共不超过900次</p><p>对于100%的数据S&lt;=2000, 修改和查询次数一共不超过70000次</p>
</div>
</div>