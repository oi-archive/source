<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Z小镇是一个景色宜人的地方，吸引来自各地的观光客来此旅游观光。<br> Z小镇附近共有<br>N(1&lt;N≤500)个景点（编号为1,2,3,…,N），这些景点被M（0&lt;M≤5000）条道路连接着，所有道路都是双向的，两个景点之间可能有多条道路。也许是为了保护该地的旅游资源，Z小镇有个奇怪的规定，就是对于一条给定的公路Ri，任何在该公路上行驶的车辆速度必须为Vi。频繁的改变速度使得游客们很不舒服，因此大家从一个景点前往另一个景点的时候，都希望选择行使过程中最大速度和最小速度的比尽可能小的路线，也就是所谓最舒适的路线。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数，N和M。<br> 接下来的M行每行包含三个正整数：x，y和v（1≤x,y≤N，0 最后一行包含两个正整数s，t，表示想知道从景点s到景点t最大最小速度比最小的路径。s和t不可能相同。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果景点s到景点t没有路径，输出&ldquo;IMPOSSIBLE&rdquo;。否则输出一个数，表示最小的速度比。如果需要，输出一个既约分数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1<br> 4 2<br> 1 2 1<br> 3 4 2<br> 1 4<br> <br> 样例2<br> 3 3<br> 1 2 10<br> 1 2 5<br> 2 3 8<br> 1 3<br> <br> 样例3<br> 3 2<br> 1 2 2<br> 2 3 4<br> 1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>样例1<br> IMPOSSIBLE<br> <br> 样例2<br> 5/4<br> <br> 样例3<br> 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N(1&lt;N≤500)</p>
<p>M（0&lt;M≤5000）</p>
<p>Vi在int范围内</p>
</div>
</div>