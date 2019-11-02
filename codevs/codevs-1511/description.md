<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>SimCity<span style="">共有</span><span style="font-family: 'Times New Roman';">n</span><span style="">个街区，编号分别是</span><span style="font-family: 'Times New Roman';">1,2,...,n,SimCity</span><span style="">的高速公路都是直接连接两个不同的街区，而且是单行的，你作为</span><span style="font-family: 'Times New Roman';">SimCity</span><span style="">的工程师接到修建</span><span style="font-family: 'Times New Roman';">m</span><span style="">条高速公路的任务，但是懒惰的你决定不按照指定的任务而是按照自己的计划修建公路，你所制定的修建计划需要满足以下两个条件</span><span style="font-family: 'Times New Roman';">:</span></p>
<p>1.<span style="">如果在任务的</span><span style="font-family: 'Times New Roman';">m</span><span style="">条公路中</span><span style="font-family: 'Times New Roman';">i</span><span style="">可以到达</span><span style="font-family: 'Times New Roman';">j,</span><span style="">那么在你的修建计划里</span><span style="font-family: 'Times New Roman';">i</span><span style="">也一定要可以达到</span><span style="font-family: 'Times New Roman';">j</span></p>
<p>2.<span style="">如果在任务的</span><span style="font-family: 'Times New Roman';">m</span><span style="">条公路中</span><span style="font-family: 'Times New Roman';">i</span><span style="">不能到达</span><span style="font-family: 'Times New Roman';">j,</span><span style="">那么在你的修建计划里</span><span style="font-family: 'Times New Roman';">i</span><span style="">也不能到达到</span><span style="font-family: 'Times New Roman';">j</span></p>
<p>3.<span style="">你的修建计划必须使在满足前两个条件的情况下修建的公路条数最小</span></p>
<p> </p>
<p>约束条件：</p>
<p>3&lt;=n&lt;=2,000 3&lt;=m&lt;=20,000</p>
<p>%40<span style="">的数据满足</span><span style="font-family: 'Times New Roman';">m&lt;=2,000</span></p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件的第一行是两个整数<span style="font-family: 'Times New Roman';">n</span><span style="">和</span><span style="font-family: 'Times New Roman';">m</span><span style="">，</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">m</span><span style="">行，每行两个整数</span><span style="font-family: 'Times New Roman';">i,j</span><span style="">，表示你的任务里包括修建一条从</span><span style="font-family: 'Times New Roman';">i</span><span style="">到达</span><span style="font-family: 'Times New Roman';">j</span><span style="">的单向高速公路</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件的第一行为一个整数<span style="font-family: 'Times New Roman';">t</span><span style="font-family: 宋体;">表示你的计划中修建需要修建的公路条数</span><span style="font-family: 'Times New Roman';">,</span></p>
<p class="p0">接下来<span style="font-family: 'Times New Roman';">t</span><span style="font-family: 宋体;">行，每行两个整数</span><span style="font-family: 'Times New Roman';">i,j</span><span style="font-family: 宋体;">，表示你的计划中包括修建一条从</span><span style="font-family: 'Times New Roman';">i</span><span style="font-family: 宋体;">到达</span><span style="font-family: 'Times New Roman';">j</span><span style="font-family: 宋体;">的单向高速公路</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 6</p>
<p>1 2</p>
<p>1 3</p>
<p>1 4</p>
<p>2 3</p>
<p>2 4</p>
<p>3 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>1 2</p>
<p>2 3</p>
<p>3 4</p>

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