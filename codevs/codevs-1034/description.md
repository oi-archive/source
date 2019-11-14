<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>由于人类对自然的疯狂破坏，人们意识到在大约2300年之后，地球不能再居住了，于是在月球上建立了新的绿地，以便在需要时移民。令人意想不到的是，2177年冬由于未知的原因，地球环境发生了连锁崩溃，人类必须在最短的时间内迁往月球。<br>现有n个太空站处于地球与月球之间（编号1..n），m艘公共交通太空船在其中来回穿梭，每个太空站Si可容纳无限的人，每艘太空船pi只可容纳Hpi人。对于每一艘太空船pi，将周期性地停靠一系列的太空站（Si1,Si2…Sir），如：（1，3，4）表示停靠太空站1 3 4 1 3 4 1 3 4 …。 任一艘太空船从任一个太空站驶往另一个任意的太空站耗时为1。人只能在太空船停靠太空站（或地球、月球）时上船或下船。初始时的人全在地球上，太空船全在初始站（太空船pi处于Si1），目标是让所有的人尽快地全部转移到月球上。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>文件第一行为三个正整数 n（太空站个数）、 m（太空船个数）、 k（需要运送的地球上的人的个数），其中 1&lt;=m&lt;=13, 1&lt;=n&lt;=20, 1&lt;=k&lt;=50。<br>接下来的n行给出了太空船的信息，第i+1行说明太空船pi，此行第一个数表示pi可容纳的人数Hpi，第二个数表示pi停靠一个周期的太空站个数r，1&lt;=r&lt;=n+2, 随后r个数便是停靠的太空站的编号(Si1,Si2,…,Sir), 地球用0表示，月球用-1表示。0时刻时，所有太空船都在初始站，随后开始运行，在时刻1，2，3…等正点时刻各艘太空船停靠相应的太空站，即人只有在0,1,2…等正点时刻才能上下太空船。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>文件只有一个数，若问题有解，输出完成全部人员安全转移的时刻，否则输出0。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2 1 </p>
<p>1 3 0 1 2</p>
<p>1 3 1 2 –1</p>

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
<p> 1&lt;=m&lt;=13, 1&lt;=n&lt;=20, 1&lt;=k&lt;=50。</p>
</div>
</div>