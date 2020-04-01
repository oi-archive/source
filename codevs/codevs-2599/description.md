<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>有一个电路，上面有n<span style="">个元件。已知i</span><span style="">损坏而断开的概率是pi</span><span style="">（i=1,2,3,</span>…,n,0&lt;=pi&lt;=1<span style="">）。请你帮忙算出电路断路的概率。</span></p>
<p>元件的连接方式很简单，对电路的表示如下：</p>
<p>1<span style="">、一个元件是最小的电路，用A</span><span style="">表示元件1</span><span style="">，B</span><span style="">表示元件2</span><span style="">，以此类推。</span></p>
<p>2<span style="">、</span>K个电路组成的串联电路表示为电路1<span style="">，电路2</span>……，电路k<span style="">。</span></p>
<p>3<span style="">、</span>K个电路组成的并联电路表示为(<span style="">电路1) (</span><span style="">电路2) </span>…… (<span style="">电路k)</span></p>

<img src="/source/codevs/codevs-2599/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yNTk5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2ODU5NTMxMS45MzAuMDA2NDQwMjQ5NjM0NjguYm1w.bmp" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件cir.in<span style="">第1</span><span style="">行是一个整数n(1&lt;=n&lt;=26),</span><span style="">表示一共有多少个元件；第2</span><span style="">行是表示电路的字符串；最后是n</span><span style="">行，每行是一个实数pi(i=1,2,</span>…,n ,0&lt;=pi&lt;=1),<span style="">表示该元件断路的概率。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个实数，表示整个电路断路的概率，精确到小数点后4位。</p>

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
<p>(A,B)((C)(D),E)</p>
<p>0.2</p>
<p>0.3</p>
<p>0.4</p>
<p>0.5</p>
<p>0.6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.2992</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>(1&lt;=n&lt;=26</p>
<p>0&lt;=pi&lt;=1</p>
<p> </p>
</div>
</div>