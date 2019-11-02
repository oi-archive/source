<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Grant喜欢带着他的小狗Pandog散步。Grant以一定的速度沿着固定路线走，该路线可能自交。Pandog喜欢游览沿途的景点，不过会在给定的N个点和主人相遇。小狗和主人同时从(X<sub>1</sub>，Y<sub>1</sub>)点出发，并同时在(X<sub>n</sub>，Y<sub>n</sub>)点汇合。小狗的速度最快是Grant的两倍。当主人从一个点以直线走向另一个点时，Pandog跑向一个它感兴趣的景点。Pandog每次与主人相遇之前最多只去一个景点。</p>
<p>你现在的任务是：为Pandog寻找一条路线(有可能与主人的路线部分相同)，使它能够游览最多的景点，并能够准时与主人在给定地点相遇或者汇合。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行是两个整数N和M(  1≤N，M≤100 )；</p>
<p>输入文件第二行的N个坐标给出了Grant的散步路线，即Pandog和主人相遇地点；</p>
<p>输入文件第三行的M个坐标给出了所有Pandog感兴趣的景点。</p>
<p>所有输入的坐标均不相同，且绝对值不超过1000。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出小狗的移动路线。</p>
<p>第一行是经过的点数，第二行依次为经过的点的坐标(直角坐标系)</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4   5</p>
<p>1   4    5    7    5    2    -2    4</p>
<p>-4    -2    3    9    1    2    -1    3    8    -3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>6</p>
<p>1    4    3    9    5    7    5    2    1    2    -2    4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>最佳匹配（或网络流） 完全标准算法，难度一般</p>
</div>
</div>