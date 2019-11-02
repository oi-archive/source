<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>农夫约翰已经决定建造电网。他已经把他的农田围成一些奇怪的形状，现在必须找出安放电源的最佳位置。</p>
<p>对于每段电网都必须从电源拉出一条电线。电线可以穿过其他电网或者跨过其他电线。电线能够以任意角度铺设，从电源连接到一段电网的任意一点上（也就是，这段电网的端点上或者在其之间的任意一点上）。这里所说的“一段电网”指的是呈一条线段状的电网，并不是连在一起的几段电网。若几段电网连在一起，那么也要分别给这些电网提供电力。</p>
<p>已知所有的 F（1 &lt;= F &lt;= 150）段电网的位置（电网总是和坐标轴平行，并且端点的坐标总是整数，0 &lt;= X,Y &lt;= 100）。你的程序要计算连接电源和每段电网所需的电线的最小总长度，还有电源的最佳坐标。</p>
<p>电源的最佳坐标可能在农夫约翰的农田中的任何一个位置，并不一定是整数。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包括 F ——电网的数量。 下面的 F 行每行包括两个 X，Y 对，表示这段电网的两个端点。</p>
<p>(ps:数据中有电网是点的情况，即 68 97 68 97，这貌似与题目叙述不符，请注意 //from Error)（路人甲：貌似照做就行了，不用管，。。。）</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一行，输出三个浮点数，每个保留1位小数。假定你的电脑的输出库会正确地对小数进行四舍五入。</p>
<p>这三个数是：</p>
<p>电源最佳坐标的 X 值， 电源最佳坐标的 Y 值，和 需要的电线的总长度（要最小）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>3
0 0 0 1
2 0 2 1
0 3 2 3</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>1.0 1.6 3.7</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见描述</p>
</div>
</div>