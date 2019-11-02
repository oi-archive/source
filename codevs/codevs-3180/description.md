<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>春天到了，百花齐放，西湖公园里新设置了许多花坛，设计师想用不同的花摆出不同的图案以吸引游人，于是设计了各种图案并且在花圃中选好了要摆放的花。不幸的是负责搬运和摆放的工人因为临时有事，只将花放到花架上就匆匆离开了，并没有按照设计师原来的设计方案摆放，结果花坛杂乱不堪,设计师只好自己来调整花的位置。由于设计师通常从事脑力劳动，较少从事搬运和摆放花盆的体力工作，所以请你帮忙找出一种移动方法使工作量最小。</p>
<p> </p>
<p>不同种类的花有不同的类型编号，虽然地球上花的种类很多，但因为公园里的花不超过1,000,000种，所以花的类型编号不超过1,000,000。另一方面，出于美学考虑，一个花坛里摆放的不同种类的花不超过3种，且不同种类的花的数量不可太接近，对于任意两种花，数量多的花的盆数至少是数量少的花的2倍。</p>
<p> </p>
<p>花坛是正六边形的，共摆放有19盆花，每盆花都放在一个转盘上，转动一盆花下面的转盘，会使周围的6盆花顺时针或逆时针移动一个位置（但不可把花转到花坛外），称为一次操作。你的任务：用最少的操作使花坛由初始状态转化为符合设计图纸的目标状态。</p>
<p> </p>
<p>例如：  </p>
<p> 详见图片</p>
<p>如图，只需将处于圆心位置的那盆花的转盘顺时针转动一个位置，红色的花就移动到了目标位置。</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入共11行，1~5行描述花坛的初始状态，7~11行表示花盆应摆放的位置。中间以空行分隔。5行数字分别表示花坛的5个行，其中第1、5两行有3个整数，第2、4两行有4个整数，第3行有5个整数，表示每一行的花的类型，不同的数代表不同种类的花。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出第一行包含一个整数T即最少的操作数，数据保证20步之内有解。以下T行输出操作序列，每行代表一次操作，包括3个整数Xi,Yi,Ki,（Xi,Yi）表示第i步转动第Xi行，第Yi盆花下的转盘，当Ki为0时表示向顺时针方向转动，Ki为1时表示向逆时针方向转动，如有多种方案，任意输出其中一种即可。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p> 1 1 1</p>
<p> 1 2 1 1</p>
<p>1 1 1 1 1</p>
<p> 1 1 1 1</p>
<p>  1 1 1</p>
<p> </p>
<p>  1 1 1</p>
<p> 1 1 1 1</p>
<p>1 1 2 1 1</p>
<p> 1 1 1 1</p>
<p>  1 1 1</p>

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
<p>3 2 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>详见试题</p>
</div>
</div>