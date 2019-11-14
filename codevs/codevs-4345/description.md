<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>jrMz 这次穿越到了《东京喰种》的世界,在得知了原本的剧情之后,经过一番慎重的考虑,<br>jrMz 决定穿越到雏实的妈妈被白鸠盯上并干掉的时候( = =我不会告诉你以 jrMz 一米五的身<br>高他刚好可以泡雏实 MM 的……),他打算把店长引到事发现场,救下雏实的妈妈(挟恩图<br>报啊!!!!!),不过安定区的路线非常复杂,并且每个岔道口都会有白鸠盯梢,通过会很麻烦,<br>所以 jrMz 要了解安定区可能有多少个岔道口,方便计算将店长引过去的时间(如果出了问<br>题救不到人,泡不到雏实 MM 的话,你以为 jrMz 会放过你吗?)。已知安定区有 N 条不重<br>合的街道(街道无限长),且任意三条街道不会交于一个岔道口。依次给出 M 个条件,每个<br>条件有三个参数 T,X,Y,若 T=0,则表示第 X 条街道与第 Y 条街道平行;若 T=1,则表示<br>它们垂直。每个条件给出后,你需要进行回答:如果该条件不会与前面的正确条件矛盾,则<br>认为该条件也是正确的,并且输出在所有正确条件(包括这个条件)的约束下,这 N 条街<br>道最多和最少能形成多少个岔道口;如果产生矛盾,则认为该条件不是正确条件。<br>在你的帮助下, jrMz 终于让店长救出了雏实的妈妈,然后 jrMz 刚想实施他下一个邪恶的计<br>划,动漫穿越器把他拖走了。( jrMz:我还不想走……55555)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行,两个正整数 N,M,有空格隔开。<br>接下来共 M 行,每行三个整数 T,X,Y,有空格隔开。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>共 M 行,各行依次对于各个给出的条件,如果该条件被认为是正确条件,则输出两个数,<br/>分别为这 N 条直线形成的交点数的最大值和最小值,有空格隔开;否则, 该行仅有一个数<br/><strong>-1</strong>。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4<br>1 1 2<br>1 2 3<br>1 1 3<br>0 2 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6 3<br>5 3<br>-1<br>4 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于第一个条件，由于还没有别的正确条件，不会产生矛盾，因此认为它是正确的。</p><p>此时交点最多（ 6 个）的情况：</p><p><img src="/source/codevs/codevs-4345/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00MzQ1L2h0dHA6Ly9pbWcuaG9vcDguY29tL2F0dGFjaG1lbnRzLzE1MTAvMTU3MzY2NDQxNzAzMC5wbmc=.png"></p><p>交点最少（ 3 个）的情况：</p><p><img src="/source/codevs/codevs-4345/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00MzQ1L2h0dHA6Ly9pbWcuaG9vcDguY29tL2F0dGFjaG1lbnRzLzE1MTAvMTkzMzY2NDQxNzAzMC5wbmc=.png"></p><p>对于第二个条件，不会与第一个条件产生矛盾，因此认为它是正确条件，并且能得到第 1</p><p>条直线与第 3 条直线是平行的。</p><p>则此时交点最多（ 5 个）的情况：</p><p><img src="/source/codevs/codevs-4345/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00MzQ1L2h0dHA6Ly9pbWcuaG9vcDguY29tL2F0dGFjaG1lbnRzLzE1MTAvMjQ4MzY2NDQxNzAzMC5wbmc=.png"></p><p>交点最少（ 3 个）的情况：</p><p><img src="/source/codevs/codevs-4345/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00MzQ1L2h0dHA6Ly9pbWcuaG9vcDguY29tL2F0dGFjaG1lbnRzLzE1MTAvMTkzMzY2NDQxNzAzMC5wbmc=.png"></p><p>对于第三个条件，因为已经能够推理出第 1 条直线与第 3 条直线平行，它们不可能同时垂直，</p><p>产生矛盾，因此不认为这个条件是正确的。</p><p>对于第四个条件，它不会与前面的正确条件产生矛盾，认为它是正确的。这时四条街道形成</p><p>的交点只能是 4 个：</p><p><img src="/source/codevs/codevs-4345/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00MzQ1L2h0dHA6Ly9pbWcuaG9vcDguY29tL2F0dGFjaG1lbnRzLzE1MTAvNzAxMzY2NDQxNzAzMC5wbmc=.png"></p><hr><p>数据范围：</p><p><img src="/source/codevs/codevs-4345/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00MzQ1L2h0dHA6Ly9pbWcuaG9vcDguY29tL2F0dGFjaG1lbnRzLzE1MTAvNTk0MzY2NDQxNzAzMC5wbmc=.png"></p>
</div>
</div>