<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: SimSun;">市内有</span><span style="font-family: Liberation Serif, serif;"><span style="">n</span></span><span style="font-family: SimSun;">个路口和</span><span style="font-family: Liberation Serif, serif;"><span style="">m</span></span><span style="font-family: SimSun;">条双向道路</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">每条道路都有过路费</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">第</span><span style="font-family: Liberation Serif, serif;"><span style="">i</span></span><span style="font-family: SimSun;">条道路的过路费 为</span><span style="font-family: Liberation Serif, serif;"><span style="">wi</span></span><span style="font-family: SimSun;">元。市内还有</span><span style="font-family: Liberation Serif, serif;"><span style="">k</span></span><span style="font-family: SimSun;">条公交线路</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">公交车只在路口停靠</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">而且一路公交车只会沿着固定的线路往返行驶。上第</span><span style="font-family: Liberation Serif, serif;"><span style="">i</span></span><span style="font-family: SimSun;">路公交车需要</span><span style="font-family: Liberation Serif, serif;"><span style="">bi</span></span><span style="font-family: SimSun;">元的费用</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">但费用是一次性的</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">, </span></span></span></span><span style="font-family: SimSun;">即你可以在公交线路上的任意停靠路口下车。但是一旦下车了</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">如果要再次上车</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">, </span></span></span></span><span style="font-family: SimSun;">则还需要再次付费。 </span> </p><p><span style="font-family: SimSun;">现在你在路口</span><span style="font-family: Liberation Serif, serif;"><span style="">S<span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">你想知道从</span><span style="font-family: Liberation Serif, serif;"><span style="">S</span></span><span style="font-family: SimSun;">出发到其它每个路口的最小费用是多少。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: SimSun;">输入的第一行包含四个整数</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">n</span></span></span></span><span style="font-family: SimSun;">、</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">m</span></span></span></span><span style="font-family: SimSun;">、</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">k</span></span></span></span><span style="font-family: SimSun;">和</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">s</span></span><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">分别代表路口数、道路数、公交 线路数和你所处的路口编号。 </span> </p><p><span style="font-family: SimSun;">接下来的</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">m</span></span></span></span><span style="font-family: SimSun;">行</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">每行包含三个整数</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">xi</span></span></span></span><span style="font-family: SimSun;">、</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">yi</span></span></span></span><span style="font-family: SimSun;">和</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">ki</span></span><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">代表第</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">i</span></span></span></span><span style="font-family: SimSun;">条道路连接</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">xi</span></span></span></span><span style="font-family: SimSun;">路口和 </span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">yi</span></span></span></span><span style="font-family: SimSun;">路口</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">并且通过这条道路需要缴纳</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">ki</span></span></span></span><span style="font-family: SimSun;">元的过路费。 </span> </p><p><span style="font-family: SimSun;">接下来的</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">k</span></span></span></span><span style="font-family: SimSun;">行</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">每行首先是两个整数</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">bi</span></span></span></span><span style="font-family: SimSun;">和</span><span style="font-family: Liberation Serif, serif;"><span style="">ti<span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">代表第</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">i</span></span></span></span><span style="font-family: SimSun;">路公交车的上车费用为</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">bi</span></span></span></span><span style="font-family: SimSun;">元</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">而且公交线路共有</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">ti</span></span></span></span><span style="font-family: SimSun;">个停靠路口。接下来同一行内有</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: CambriaMath;"><span style="">ti</span></span></span></span><span style="font-family: SimSun;">个整数</span><span style="font-family: Liberation Serif, serif;"><span style=""><span style="font-family: SimSun;"><span style="">,</span></span></span></span><span style="font-family: SimSun;">按顺序给出 了这路公交车的各个停靠路口。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: 12pt; font-family: SimSun;">输出一行,包含 n&nbsp;</span><span style="font-size: 12pt; font-family: SimSun;">个整数,为从路口 S 到每个路口的最小费用</span><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: CourierNewPSMT;">5 4 1 1</span><br></p><p><span style="font-family: 'CourierNewPSMT';">1 2 1</span></p><p><span style="font-family: 'CourierNewPSMT';">2 3 1</span></p><p><span style="font-family: 'CourierNewPSMT';">3 4 1</span></p><p><span style="font-family: 'CourierNewPSMT';">4 5 1</span></p><p><span style="font-family: 'CourierNewPSMT';">2 4 2 3 4 5 </span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: CourierNewPSMT;">0 1 2 3 3</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: SimSun;">到路口 </span><span style="font-family: TimesNewRomanPSMT;">5 </span><span style="font-family: SimSun;">时需要先走到路口 </span><span style="font-family: TimesNewRomanPSMT;">2 </span><span style="font-family: SimSun;">然后搭公交车,费用为</span><span style="font-family: CambriaMath;">1 + 2 = 3</span><span style="font-family: SimSun;">。 </span><br></p>
</div>
</div>