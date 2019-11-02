<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>终于，破解了千年的难题。小<span style="font-family: 'Times New Roman';">FF</span><span style="">找到了王室的宝物室，里面堆满了无数价值连城的宝物……这下小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">可发财了，嘎嘎。但是这里的宝物实在是太多了，小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">的采集车似乎装不下那么多宝物。看来小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">只能含泪舍弃其中的一部分宝物了……小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">对洞穴里的宝物进行了整理，他发现每样宝物都有一件或者多件。他粗略估算了下每样宝物的价值，之后开始了宝物筛选工作：小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">有一个最大载重为</span><span style="font-family: 'Times New Roman';">W</span><span style="">的采集车，洞穴里总共有</span><span style="font-family: 'Times New Roman';">n</span><span style="">种宝物，每种宝物的价值为</span><span style="font-family: 'Times New Roman';">v [i]</span><span style="">，重量为</span><span style="font-family: 'Times New Roman';">w [i]</span><span style="">，每种宝物有</span><span style="font-family: 'Times New Roman';">m[i]</span><span style="">件。小</span><span style="font-family: 'Times New Roman';">FF</span><span style="">希望在采集车不超载的前提下，选择一些宝物装进采集车，使得它们的价值和最大。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为一个整数<span style="font-family: 'Times New Roman';">N</span><span style="">和</span><span style="font-family: 'Times New Roman';">W</span><span style="">，分别表示宝物种数和采集车的最大载重。</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">n</span><span style="">行每行三个整数，其中第</span><span style="font-family: 'Times New Roman';">i</span><span style="">行第一个数表示第</span><span style="font-family: 'Times New Roman';">i</span><span style="">类品价值，第二个整数表示一件该类物品的重量，第三个整数为该类物品数量。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出仅一个整数<span style="font-family: 'Times New Roman';">ans</span><span style="font-family: 宋体;">，表示在采集车不超载情况下收集宝物的最大价值。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 20</p>
<p>3 9 3</p>
<p>5 9 1</p>
<p>9 4 2</p>
<p>8 1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>47</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】</p>
<p>对于<span style="font-family: 'Times New Roman';">30%</span><span style="">的数据：</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤∑</span><span style="font-family: 'Times New Roman';">m[i]</span><span style="">≤</span><span style="font-family: 'Times New Roman';">10^4</span><span style="">；</span><span style="font-family: 'Times New Roman';">0</span><span style="">≤</span><span style="font-family: 'Times New Roman';">w</span><span style="">≤</span><span style="font-family: 'Times New Roman';">10^3</span><span style="">。</span></p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据：</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤∑</span><span style="font-family: 'Times New Roman';">m[i]</span><span style="">≤</span><span style="font-family: 'Times New Roman';">10^5</span><span style="">；</span><span style="font-family: 'Times New Roman';">0</span><span style="">≤</span><span style="font-family: 'Times New Roman';">w</span><span style="">≤</span><span style="font-family: 'Times New Roman';">4*10^4</span><span style="">；</span><span style="font-family: 'Times New Roman';">1</span><span style="">≤</span><span style="font-family: 'Times New Roman';">n</span><span style="">≤</span><span style="font-family: 'Times New Roman';">100</span><span style="">。</span></p>
</div>
</div>