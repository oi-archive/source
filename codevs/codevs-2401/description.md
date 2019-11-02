<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>著名歌手LAALA最近迷上了一款赛车游戏，游戏中开车的玩家在不同的路段需要选择不同的速度，使得自己在最短的时间内到达终点。开始游戏时，车内的初始油量为f，所以游戏的关键是如何在速度和耗油量之间实现平衡。</p>
<p>LAALA 经过一段时间的研究后，发现这款游戏可以用一个简单的数学模型来描述，具体来说：从起点到终点的路线可以被简化成折线段，每条线段代表一个上坡或者下坡，若在一段斜率为s(s&gt;0代表上坡，s=0代表平地，s&lt;0代表下坡)的道路上以速度v km/h行驶，则每公里的耗油量为max(0,av+bs)，其中a和b为游戏的内置参数，分别表示在平地行驶时的耗油率及斜坡对耗油量的影响(b 恒为正)。这里假设，加速和减速不耗油，且看成是瞬间完成的，所以即使在同一条线段上也可采取以不同的速度行驶的策略来缩短耗费的时间。</p>
<p>由于LAALA在以前的游戏中表现不佳，现在使用的车型依然是系统初始分配的，所以它的速度不能超过vmax km/h。在获得这些参数后，LAALA想知道在初始油量受限的情况下（中途不许加油）自己能得到的最佳成绩是多少。作为LAALA的歌迷，你能帮帮他吗? </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个正整数T，表示数据组数。对每组数据，第一行是用空格隔开的4个浮点数a、b、vmax和f，其中a、b和vmax的意义如前所述，f表示初始油量，其单位也与前面的描述保持一致。第二行是一个正整数r，表示线段的数目。接下来的r行，每行是用空格隔开的2个浮点数xi和yi，分别表示在标准笛卡耳坐标系下该线段在水平方向和垂直方向的改变量(单位为米)。 </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含T行，依次对应输入中的T组数据。对某组数据，若基于初始油量无法到达终点，则对应行输出IMPOSSIBLE，否则输出最少需要的时间(单位为小时)。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><img height="274" src="/source/codevs/codevs-2401/img/aHR0cDovL3AxMy5mcmVlcC5jbi9wLmFzcHg_dT12MjBfcDEzX3Bob3RvXzEzMDUwMzIwMzAzNDI4NDFfMC5wbmc=.png" width="159"></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1.41421</p>
<p>IMPOSSIBLE</p>
<p>0.07212</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>注意单位！</strong></p>
<p>范围如图<img height="101" src="/source/codevs/codevs-2401/img/aHR0cDovL3AxMy5mcmVlcC5jbi9wLmFzcHg_dT12MjBfcDEzX3Bob3RvXzEzMDUwMzIwMzIzMzQyMTFfMC5wbmc=.png" width="705"></p>
</div>
</div>