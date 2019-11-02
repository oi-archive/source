<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">已给定一个 N个点 M条边的有向图，点编号为1到N，第i条边为 （ui，vi）， 权值为 wi。你可以进行一次操作，使得任意条边的权值变成非负整数。要求进行尽量少的操作次数，使得点 1到点 N的最短路径长度变成 c。</span><br style=""><span style="">题目保证， c小于在未进行任何操作之前的原图中 1到 N的最短路长度。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入文件tweak.in 第一行三个整数，第一行三个整数，N，M和 c<br>接下来 M行，每一条边的信息 ui，vi和 wi，第 i行的表述第 i条边的信息。 保证不会有自环存在，对于不同的 i和 j，（ui，vi）不同于 （uj，vj）。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-family: 微软雅黑, &#39;MS Sans Serif&#39;, sans-serif; font-size: 13px;">输出文件&nbsp;tweak.out&nbsp;一行一个整数，要进行最少多少次操作才能使得最短路长度变为&nbsp;c。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">3 3 3</span><br style=""><span style="">1 2 3</span><br style=""><span style="">2 3 3</span><br style=""><span style="">1 3 8</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">    N&lt;=100</span><br style=""><span style="">    M&lt;=1000</span><br style=""><span style="">    0&lt;=c&lt;=100000</span><br style=""><span style="">    0&lt;=wi&lt;=10000</span><br style=""><span style="">    30%数据满足 M&lt;=20</span><br style=""><span style="">    50%数据满足 M&lt;=70</span></p>
</div>
</div>