<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>背景：suntian正准备将飞翔带回圣殿，不料一声巨响，suntian的三维时空被飞翔炸开，飞翔再次出现在suntian面前，两人同时出手……随着两人昏天暗地的打斗，时空开始扭曲并产生波动，影响了suntian施咒，然而就是这一下，飞翔抓住了时机，释放巨大的能量将suntian送入了一个扭曲的四维时空……</p>
<p> </p>
<p>描述：为了快一点追到飞翔,suntian希望在最短的时间内逃出这个四维时空。</p>
<p> </p>
<p> </p>
<p>他马上集中精力，在0.0000000000000001ms之内找到了这个时空的奇点。令他吃惊的是，这个空间竟然有n个奇点！这让suntian摸不着头脑。但作为圣殿战士，suntian也不是吃素的，他在冥思苦想之后得出了一个结论：只有在某个奇点处用咒术将其他n-1个奇点拉到这个奇点，才能将奇点打开。但是，将奇点拉拽到另一个奇点耗费的能量不同。能量W为：trunc(sqrt((x1-x2)^2+(y1-y2)^2+(z1-z2)^2))+abs(t1-t2) Tas。奇点拉在一起将被合并，suntian可以先把某些奇点合并再拉到他所处的奇点。为了抓捕到飞翔，suntian想用最少的能量来打开奇点，但是suntian能量已经所剩不多了。那么，suntian能否逃脱呢？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，为n(0&lt;n&lt;=10^3,n∈N)。</p>
<p>第2至n+1行，为每行的坐标x,y,z,t(0&lt;x,y,z,t&lt;=10^4,x,y,z,t∈N)。 第n+2行，为suntian剩余能量L(0&lt;L&lt;maxlongint,L∈N)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共一行。</p>
<p>&nbsp;如果所用最少能量tot&gt;L，那么输出&ldquo;Death&rdquo;；</p>
<p>&nbsp;否则，输出tot。(tot&lt;maxlongint)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>1 1 1 1</p>
<p>1 1 1 2</p>
<p>2 2 2 2</p>
<p>3 3 3 3</p>
<p>3 3 3 4</p>
<p>5Tas</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5Tas</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据提示上面有。</p>
</div>
</div>