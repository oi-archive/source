<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>诸一行遇到了一个难题：<span style="font-family: serif;">在一个果园里，多多已经将所有的果子打了下来，而且按果子的不同种类分成了不同的堆。多多决定把所有的果子合成一堆。</span><br style="font-family: serif;"><span style="font-family: serif;">每一次合并，多多可以把两队果子合并到一起，消耗的体力等于两堆果子的重量之和。可以看出，所有的果子经过n-1次合并之后，就只剩下一堆了。多多在合并果子是总共消耗的体力等于每次合并所耗体力之和。</span><br style="font-family: serif;"><span style="font-family: serif;">因为还要花大力气把这些果子搬回家，所以多多在合并果子时要尽可能的节省体力。假定没个果子重量都为1，并且已知果子的种类数和每种果子的数目，你的任务是设计出合并的次序方案，是多多消耗的体力最少，并输出这个最小的体力耗费值。</span><br style="font-family: serif;"><span style="font-family: serif;">例如有3种果子，数目以此为1、2、9.可以先将1,2堆合并，新堆数目为3，消耗体力为3.接着，将新堆与原先的第三堆合并，有得到新的堆，数目为12，耗费体力为12。所以多多总共消耗费体力=3+12=15。可以证明15为最小的体力耗费值。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: serif;">第一行是一个整数n（1≤n≤100000），表示果子的种类数。第二行包含n个整数，用空格分隔，第i个整数a（1≤a≤20000）是第i种果子的数目。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="color: rgb(51, 51, 51); font-family: serif; font-size: small; line-height: 18px; background-color: rgb(228, 240, 248);">一个整数，即最小的体力耗费值。输入数据保证这个值小于2^31.</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">3
1 2 9</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">15</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">对于30%的数据，保证有n≤1000</span><br style="font-family: monospace;"><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: monospace;">对于50%的数据，保证有n≤5000</span><br style="font-family: monospace;"><br style="font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;"><span style="font-family: monospace;">对于全部的数据，保证有n≤100000</span></p>
</div>
</div>