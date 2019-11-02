<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>2010年，世博会在中国上海举办，吸引了数以千万计的中外游客前来参观。暑假期间小Z也来到了上海世博园， 她对世博园的拥挤早有所闻，对有的展馆甚至要排上好几个小时的队才能进入也做好了充分准备，但为了使得自己的世博之旅更加顺利舒畅，小Z决定在游玩之前先 制定一份详细的旅行路线。</p>
<p>小Z搜集到了世博园的地图，她发现从整体上看世博园是一块非常狭长的区域，而每一个展馆占用了其中一个几乎相同大小的方块。因此可以将整个园区看成一个n × m的矩阵(n≤3)，其中每一个格子为一个主题展馆。</p>
<p>由于不同展馆受到的关注度会有一些差别，因此排队时间的长短也不尽相同。小Z根据统计信息给每一个展馆(x, y)标记了Tx,y = 0或1，如果Tx,y = 1，表示这个展馆非常热门，需要排很长时间的队；如果Tx,y = 0，表示这个展馆相对比较普通，几乎不需要排队即可进入参观。小Z希望能够制定一份合理的路线，使得能交替参观热门馆和普通馆，既不会因为总是参观热门馆 而长时间在排队，也不会因为总是参观普通馆而使得游览过于平淡。同时，小Z办事很讲究效率，她希望在游遍所有展馆的同时，又不会走冤枉路浪费体力。因此她希望旅行路线满足以下几个限制：</p>
<ol>
<li>在参观完位于(x, y)的展馆后，下一个参观的是一个相邻的且未被参观过的展馆(x', y')，即 |x-x'|+|y-y'|=1；</li>
<li>路线的起点位于整个矩阵的边界上，即x = 1或x = n或y = 1或y = m；</li>
</ol>
<p>她制定了一个长度为n*m的 01 序列L，她希望第i个参观的展馆(x,y)满足T<sub>x,y</sub>=L<sub>i</sub>。</p>
<p>小Z想知道有多少条不同的旅行路线能够满足她的要求。由于最终的结果可能很大，小Z只想知道可行的旅行路线总数<strong>mod</strong> 11192869的值。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件trip.in第一行包含两个正整数n, m。</p>
<p>第2行至第n+ 1行，每行有m个01整数，其中第i+ 1行第j个数表示T<sub>i,j</sub>。</p>
<p>第n+ 2行有n*m个01整数，其中第i个数表示L<sub>i</sub>的值。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">输出文件trip.out仅包含一个整数，表示可行的旅行路线总数mod 11192869的值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 2</p>
<p>10</p>
<p>01</p>
<p>1010</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><strong>【样例说明】</strong></p>
<p>这四条可行的旅行路线分别为：</p>
<p>(1,1)→(1,2)→(2,2)→(2,1)</p>
<p>(1,1)→(2,1)→(2,2)→(1,2)</p>
<p>(2,2)→(1,2)→(1,1)→(2,1)</p>
<p>(2,2)→(2,1)→(1,1)→(1,2)</p>
<p><strong>【数据规模和约定】</strong></p>
<p>对于10%的数据：n=1；</p>
<p>对于30%的数据：n=2；</p>
<p>对于60%的数据：n= 3，其中20%的数据T<sub>i,j</sub>全为0；</p>
<p>对于100%的数据：m≤50，L<sub>i</sub>, T<sub>i,j</sub> = 0或1。</p>
<p> </p>
<p>注意是10s</p>
</div>
</div>