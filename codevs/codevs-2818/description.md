<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　剧情接上题：KingerTangent的愤怒</span></p>
<p><span>　　萌化的tangjz拥有了修补大地的力量，他决定为了这些有着信仰的OIer们，使得这些OIer们能重聚。</span></p>
<p><span><span>　　现在的OI村在tangjz的探测器上是一幅N*M的网格图，行和列的标号都是从0开始的，其中有一些地方是黑色的，表示此处土地在海平面之上(OIer只能在海平面之上)，还有一些地方是白色的，表示此处土地在海平面之下，创造一块土地(即将一个白格子变成黑色的)的代价是1。</span></span></p>
<p><span><span><span>　　其中有K块黑色格子上有幸存的OIer群。</span></span></span></p>
<p><span><span><span><span>　　由于tangjz想要节省力量去修复更多不和谐的事物，所以他要用最少的代价将这个K个OIer群连通。(这里的连通是指四联通，即上下左右连通)</span></span></span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行两个正整数N和M，表示tangjz的探测范围。</p>
<p>　　接下来N行，每行一个长度为M的01串，即探测图。(其中0表示白色，1表示黑色)</p>
<p>　　第N+2行一个正整数K，表示有OIer群的个数。</p>
<p>　　接下来K行，每行两个非负整数X<sub>i</sub>和Y<sub>i</sub>，表示第i个OIer群在探测器上的坐标。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　一个正整数Ans，表示最小代价。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5<br>10101<br>01010<br>10101<br>01010<br>10101<br>2<br>0 0<br>4 4</p>

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
<p>对于30%的数据:<img src="/source/codevs/codevs-2818/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_TipNXGxlcSZhbXA7c3BhY2U7NTA=.latex"><br>对于50%的数据:<img src="/source/codevs/codevs-2818/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_SyZhbXA7c3BhY2U7PSZhbXA7c3BhY2U7Mg==.latex"><br>对于60%的数据:<img src="/source/codevs/codevs-2818/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_TipNXGxlcSZhbXA7c3BhY2U7NTAw.latex"><br>对于100%的数据:<img src="/source/codevs/codevs-2818/img/aHR0cDovL2xhdGV4LmNvZGVjb2dzLmNvbS9naWYubGF0ZXg_bWluKE4sTSlcbGVxJmFtcDtzcGFjZTsxMCxtYXgoTixNKVxsZXEmYW1wO3NwYWNlOzEwMA==.latex"> ，K不大于初始状态下黑格子的数量。</p>
</div>
</div>