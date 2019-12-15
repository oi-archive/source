<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style=""><span style="">毛大神由于最近学习压力很大</span><span style="font-family: 'MS Mincho';">，</span><span style="">于是召集了一群小伙伴一起去探险。</span></span></p><p style=""><span style=""><span style="">这批探险队员正在一个迷宫一样的山洞里摸索</span><span style="font-family: 'MS Mincho';">，</span><span style="">突然她们得到了一个糟糕的消息</span><span style="font-family: 'MS Mincho';">，</span><span style="">由于附近发生地</span></span><span style="">震</span><span style="font-family: 'MS Mincho';">，</span><span style="">这个山洞将有可能在 T 个单位时间后坍塌。现在她们要用最快的速度找出一个方案</span><span style="font-family: 'MS Mincho';">，</span><span style="">使得在 T 个单 位时间内逃出的队员最多。已知每个探险队员在一个单位时间内可以向前后左右任一方向移动一格</span><span style="font-family: 'MS Mincho';">，</span><span style="">也</span><span style="">可以停留在原地不动。有一个更糟糕的情况是</span><span style="font-family: 'MS Mincho';">，</span><span style="">虽然山洞的内部比较宽敞</span><span style="font-family: 'MS Mincho';">，</span><span style="">但山洞的出口都非常狭窄</span><span style="font-family: 'MS Mincho';">，</span><span style=""> 一个单位时间只能允许一名队员通过。</span><span style="">山洞的地图用一个 R 行</span><span style="font-family: 'MS Mincho';">×</span><span style="">C 列的字符矩阵表示</span><span style="font-family: 'MS Mincho';">，</span><span style="">其中'.'表示在开始的时候没有探险队员的空地</span><span style="font-family: 'MS Mincho';">，</span><span style="">空</span><span style="">地可以容纳任意多的探险队员</span><span style="font-family: 'MS Mincho';">；</span><span style="">'P'表示在开始的时候有探险队员的空地</span><span style="font-family: 'MS Mincho';">，</span><span style="">我们假设在开始的时候所有 的队员都在不同的位置上</span><span style="font-family: 'MS Mincho';">，</span><span style="">且没有队员恰好位于出口所在的方格</span><span style="font-family: 'MS Mincho';">；</span><span style="">'*'表示障碍物</span><span style="font-family: 'MS Mincho';">，</span><span style="">探险队员不能经过 被障碍物占据的方格</span><span style="font-family: 'MS Mincho';">；</span><span style="">'O'(大写字母 O)表示出口</span><span style="font-family: 'MS Mincho';">，</span><span style="">输入数据保证出口一定位于地图的边界上</span><span style="font-family: 'MS Mincho';">，</span><span style="">即只有第</span><span style="">1 行,第 R 行,第 1 列,第 C 列有可能出现'O'。另外</span><span style="font-family: 'MS Mincho';">，</span><span style="">输入数据保证整个地图被边界和出口围住</span><span style="font-family: 'MS Mincho';">，</span><span style="">即第 1</span><span style="">行,第 R 行,第 1 列,第 C 列只能是'*'或'O'。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">第一行是用空格隔开的两个整数 R 和 C</span><span style="font-family: 'MS Mincho';">，</span><span style="">表示地图的大小。 第二行是整数 T</span><span style="font-family: 'MS Mincho';">，</span><span style="">即山洞将要坍塌的时间。</span></p><p style=""><span style="">接下来 R 行</span><span style="font-family: 'MS Mincho';">，</span><span style="">每行包含 C 个字符</span><span style="font-family: 'MS Mincho';">，</span><span style="">表示一幅山洞地图。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="line-height: 16px;"><span style="font-size:14px;font-family:宋体">输出共一行</span><span style="font-size:14px;font-family:&#39;MS Mincho&#39;">，</span><span style="font-size:14px;font-family:宋体">包含一个整数</span><span style="font-size:14px;font-family:&#39;MS Mincho&#39;">，</span><span style="font-size:14px;font-family:宋体">即 T 个单位时间内最多能逃出的人数。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">5 5</span></p><p style=""><span style="">4</span></p><p style="">*****<br></p><p style="">*P..*</p><p style="">O**.O</p><p style="">*P..*</p><p style="">*****</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: 'Times New Roman';"> </span></p><p style=""><span style="">【样例解释】 山洞有两个出口</span><span style="font-family: 'MS Mincho';">，</span><span style="">但只有右边的出口是可以到达的。虽然在 3 个单位时间内两人都可以到达出口左</span><span style="">侧的方格处</span><span style="font-family: 'MS Mincho';">，</span><span style="">但由于在出口处一个单位时间只能允许一人通过</span><span style="font-family: 'MS Mincho';">，</span><span style="">故 4 个单位时间内只能逃出一人。两人 都逃出需要 5 个单位时间。</span><span style=""> 对于 </span><span style="font-family: 'Courier New';">30%</span><span style="">的数据</span><span style="font-family: 'MS Mincho';">：</span><span style="">队员数和出口数均不超过 </span><span style="font-family: 'Courier New';">10</span><span style="font-family: 'MS Mincho';">；</span><span style="">对于 </span><span style="font-family: 'Courier New';">100%</span><span style="">的数据</span><span style="font-family: 'MS Mincho';">：</span><span style="font-family: 'Courier New';">3≤R,C≤12</span><span style="font-family: 'MS Mincho';">；</span><span style="font-family: 'Courier New';">0</span><span style="font-family: 'MS Mincho';">＜</span><span style="font-family: 'Courier New';">T≤50</span></p><p style=""><span style=""></span><br></p><p><br></p>
</div>
</div>