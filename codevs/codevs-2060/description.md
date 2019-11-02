<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>　　现在有N块积木，每块积木都有自重Weight和正常状态下的承重能力Force，现在要把这N块积木垒在一起，但是有可能某块积木的负重超过了它在正常状态下的承重能力，那么这块积木就有被压坏的危险，请问应该如何堆这N块积木使得N块积木中最大的压力指数最小。</p>
<p>　　这里定义压力指数为该积木的负重与其在正常状态下的承重能力的差值。</p>
<p> </p>
<p>原题：Usaco NOV05 Sliver 奶牛杂技(Cow Acrobats)</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>　　第一行为一个正整数N，表示有N块积木。<br>　　第二行到第 N+1 行，每行两个整数数，分别是第i个积木的Weight和Force。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>　　输出共一行，表示最大压力指数的最小值。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2<br>100 0<br>1000 100</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例解释：<br>　　把Weight为100的积木放在Weight为1000的积木上，下面积木的压力指数为100 - 100 = 0，另外一块积木的压力指数和它的相等。</p>
<p> </p>
<p>　　对于30% 的数据，1 &lt;= N &lt;= 3<br>　　对于60% 的数据，1 &lt;= N &lt;= 1000<br>　　对于100%的数据，1 &lt;= N &lt;= 50000<br>　　对于100%的数据，1 &lt;= Weight &lt;= 10000，1 &lt;= Force &lt;= 10<sup>9</sup></p>
</div>
</div>