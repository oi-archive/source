<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>由于人类对自然资源的消耗，人们意识到大约在2300 年之后，地球就不能再居住了。<br>于是在月球上建立了新的绿地，以便在需要时移民。令人意想不到的是，2177 年冬由于未<br>知的原因，地球环境发生了连锁崩溃，人类必须在最短的时间内迁往月球。现有n个太空站<br>位于地球与月球之间，且有m 艘公共交通太空船在其间来回穿梭。每个太空站可容纳无限<br>多的人，而每艘太空船i 只可容纳H[i]个人。每艘太空船将周期性地停靠一系列的太空站，<br>例如：(1，3，4)表示该太空船将周期性地停靠太空站134134134…。每一艘太空船从一个太<br>空站驶往任一太空站耗时均为1。人们只能在太空船停靠太空站(或月球、地球)时上、下船。<br>初始时所有人全在地球上，太空船全在初始站。试设计一个算法，找出让所有人尽快地全部<br>转移到月球上的运输方案。<br>«编程任务：<br>对于给定的太空船的信息，找到让所有人尽快地全部转移到月球上的运输方案。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行有3 个正整数n（太空站个数），m（太空船<br>个数）和k（需要运送的地球上的人的个数）。其中 1&lt;=m&lt;=13, 1&lt;=n&lt;=20, 1&lt;=k&lt;=50。<br>接下来的m行给出太空船的信息。第i+1 行说明太空船pi。第1 个数表示pi 可容纳的<br>人数Hpi；第2 个数表示pi 一个周期停靠的太空站个数r，1&lt;=r&lt;=n+2；随后r 个数是停靠<br>的太空站的编号(Si1,Si2,…,Sir)，地球用0 表示，月球用-1 表示。时刻0 时，所有太空船都<br>在初始站，然后开始运行。在时刻1，2，3…等正点时刻各艘太空船停靠相应的太空站。人<br>只有在0,1,2…等正点时刻才能上下太空船。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>将全部人员安全转移所需的时间输出。如果问题无解，则输出0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2 1<br>1 3 0 1 2<br>1 3 1 2 –1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

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