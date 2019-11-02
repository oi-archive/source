<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>瑞瑞想要亲自修复在他的一个小牧场周围的围栏。他测量栅栏并发现他需要<span style="font-family: Times New Roman;">N</span><span style="">（</span><span style="font-family: Times New Roman;">1≤N≤20,000</span><span style="">）根木板，每根的长度为整数</span><span style="font-family: Times New Roman;">Li</span><span style="">（</span><span style="font-family: Times New Roman;">1≤Li≤50,000</span><span style="">）。于是，他神奇地买了一根足够长的木板，长度为所需的</span><span style="font-family: Times New Roman;">N</span><span style="">根木板的长度的总和，他决定将这根木板切成所需的</span><span style="font-family: Times New Roman;">N</span><span style="">根木板。（瑞瑞在切割木板时不会产生木屑，不需考虑切割时损耗的长度）</span></p>
<p>瑞瑞切割木板时使用的是一种特殊的方式，这种方式在将一根长度为<span style="font-family: Times New Roman;">x</span><span style="">的模板切为两根时，需要消耗</span><span style="font-family: Times New Roman;">x</span><span style="">个单位的能量。瑞瑞拥有无尽的能量，但现在提倡节约能量，所以作为榜样，他决定尽可能节约能量。显然，总共需要切割</span><span style="font-family: Times New Roman;">N-1</span><span style="">次，问题是，每次应该怎么切呢？请编程计算最少需要消耗的能量总和。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行: <span style="">整数</span><span style="font-family: Times New Roman;">N</span><span style="">，表示所需木板的数量</span></p>
<p>第2<span style="">到</span><span style="font-family: Times New Roman;">N+1</span><span style="">行</span>: <span style="">每行为一个整数，表示一块木板的长度</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个整数，表示最少需要消耗的能量总和</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>8</p>
<p>5</p>
<p>8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>34</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>将长度为21<span style="">的木板，第一次切割为长度为</span><span style="font-family: Times New Roman;">8</span><span style="">和长度为</span><span style="font-family: Times New Roman;">13</span><span style="">的，消耗</span><span style="font-family: Times New Roman;">21</span><span style="">个单位的能量，第二次将长度为</span><span style="font-family: Times New Roman;">13</span><span style="">的木板切割为长度为</span><span style="font-family: Times New Roman;">5</span><span style="">和</span><span style="font-family: Times New Roman;">8</span><span style="">的，消耗</span><span style="font-family: Times New Roman;">13</span><span style="">个单位的能量，共消耗</span><span style="font-family: Times New Roman;">34</span><span style="">个单位的能量，是消耗能量最小的方案。</span></p>
</div>
</div>