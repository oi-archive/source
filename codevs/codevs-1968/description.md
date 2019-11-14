<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    小Z 在玩一个叫做《淘金者》的游戏。游戏的世界是一个二维坐标。X 轴、 Y 轴坐标范围均为 1..N。初始的时候，所有的整数坐标点上均有一块金子，共 N*N 块。 <br>    一阵风吹过，金子的位置发生了一些变化。细心的小Z 发现，初始在(i, j) 坐标处的金子会变到(f(i), f(j))坐标处。其中f(x)表示x 各位数字的乘积，例如 f(99)=81，f(12)=2，f(10)=0。如果金子变化后的坐标不在1..N 的范围内，我们认 为这块金子已经被移出游戏。同时可以发现，对于变化之后的游戏局面，某些坐 标上的金子数量可能不止一块，而另外一些坐标上可能已经没有金子。这次变化 之后，游戏将不会再对金子的位置和数量进行改变，玩家可以开始进行采集工作。 小Z 很懒，打算只进行K 次采集。每次采集可以得到某一个坐标上的所有 金子，采集之后，该坐标上的金子数变为0。 现在小Z 希望知道，对于变化之后的游戏局面，在采集次数为K 的前提下， 最多可以采集到多少块金子？ <br><span style="">    答案可能很大，小Z 希望得到对1000000007取模之后的答案。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    共一行，包含两个正整数N, K 。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>&nbsp; &nbsp;一个整数，表示最多可以采集到的金子数量。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>12 5 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>18</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N≤10<sup>12</sup>，k≤100000，k≤N<sup>2</sup></p>
</div>
</div>