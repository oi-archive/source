<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>背景：suntian成功地打开了奇点。但是当suntian回到原地时，飞翔已不见了踪影。然而suntian却没有一丝慌忙。在他念了一段咒文后，他身前的时空撕裂开来，飞翔被传送了出来。原来，在飞翔将suntian送入黑洞之前，suntian已经将一个时空素(定位器)放在了飞翔的身上。于是，suntian以其人之道，还治其人之身，将飞翔送入了他制造的时空中，准备将飞翔押回圣殿。飞翔岂是等闲之辈，他在suntian的时空中正准备脱逃……</p>
<p> </p>
<p> </p>
<p>描述：飞翔发现，suntian的时空只不过是普通的三维时空(立方体),每个点都可由以这个点为顶点的单位正方体（棱长为1）的其余七个顶点到达，在所有点中有m个点上有一些黄铜。然而，飞翔却没有找到这个三维时空的奇点，只是发现了一段铭文：“To let the point appear,select one way and go along this way towards the (x,y,z) position and collect the coppers（黄铜） on this way.‘You cannot go backwards’.If you don't get "sum" coppers,the point won't appear.”不能往回走的意思是，只能是朝着正方向走。如图，即飞翔若要走到点S，那么他只能由此单位正方体的其余七个顶点走到。</p>
<p>飞翔决定，如果不能够收集到足够的黄铜，就用咒文炸开这个时空。那么，飞翔能够收集到足够的黄铜吗？（飞翔在点(1,1,1))</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，为x,y,z,(1&lt;=x,y,z&lt;=100,x,y,z∈N);</p>
<p>第二行，为m,(0&lt;=m&lt;=10^6,m∈N);</p>
<p>第3至m+2行，为每个点的坐标i,j,k以及这个点上有的黄铜数n(1&lt;=i,j,k&lt;=100,1&lt;=n&lt;=maxint, i,j,k,n∈N);</p>
<p>第m+3行，为至少需要黄铜sum的个数(0&lt;=sum&lt;=maxlongint)。</p>

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
<p>&nbsp;如果收集到的黄铜tot&gt;=sum，那么输出最大的tot(0&lt;=tot&lt;=maxlongint)；否则，输出&lsquo;BigBang!&rsquo;。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5 5</p>
<p>5</p>
<p>1 1 1 1</p>
<p>2 2 2 1</p>
<p>3 3 3 1</p>
<p>4 4 4 1</p>
<p>5 5 5 1</p>
<p>5</p>

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
<p>请看上面。</p>
</div>
</div>