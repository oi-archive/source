<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    皮尔是一个出了名的盗画者，他经过数月的精心准备，打算到艺术馆盗画。艺术馆的结构，每条走廊要么分叉为二条走廊，要么通向一个展览室。皮尔知道每个展室里藏画的数量，并且他精确地测量了通过每条走廊的时间，由于经验老道，他拿下一副画需要5秒的时间。你的任务是设计一个程序，计算在警察赶来之前(警察到达时皮尔回到了入口也算)，他最多能偷到多少幅画。</p>

<img src="/source/codevs/codevs-1163/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMTYzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvcHJvYmxlbS8xMTYzLmpwZw==.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行是警察赶到得时间，以s为单位。第2行描述了艺术馆得结构，是一串非负整数，成对地出现：每一对得第一个数是走过一条走廊得时间，第2个数是它末端得藏画数量；如果第2个数是0，那么说明这条走廊分叉为两条另外得走廊。数据按照深度优先得次序给出，请看样例</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出偷到得画得数量</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>60</p>
<p>7 0 8 0 3 1 14 2 10 0 12 4 6 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>s&lt;=600</p>
<p>走廊的数目&lt;=100</p>
</div>
</div>