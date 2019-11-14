<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style=""> </span><img height="261" src="../../../media/image/problem/1066.jpg" style="" width="361"></p>
<p><span style="">在一个遥远的国度，一侧是风景秀美的湖泊，另一侧则是漫无边际的沙漠。该国的行政 区划十分特殊，刚好构成一个N行M列的矩形，如上图所示，其中每个格子都代表一座城 市，每座城市都有一个海拔高度。 为了使居民们都尽可能饮用到清澈的湖水，现在要在某些城市建造水利设施。水利设施 有两种，分别为蓄水厂和输水站。蓄水厂的功能是利用水泵将湖泊中的水抽取到所在城市的 蓄水池中。因此，只有与湖泊毗邻的第1行的城市可以建造蓄水厂。而输水站的功能则是通 过输水管线利用高度落差，将湖水从高处向低处输送。故一座城市能建造输水站的前提，是 存在比它海拔更高且拥有公共边的相邻城市，已经建有水利设施。 由于第N行的城市靠近沙漠，是该国的干旱区，所以要求其中的每座城市都建有水利 设施。那么，这个要求能否满足呢？如果能，请计算最少建造几个蓄水厂；如果不能，求干 旱区中不可能建有水利设施的城市数目。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">输入的每行中两个数之间用一个空格隔开。 输入的第一行是两个正整数N和M，表示矩形的规模。 接下来N行，每行M个正整数，依次代表每座城市的海拔高度。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size: xx-small;">输出有两行。如果能满足要求，输出的第一行是整数1，第二行是一个整数，代表最少 建造几个蓄水厂；如果不能满足要求，输出的第一行是整数0，第二行是一个整数，代表有 几座干旱区中的城市不可能建有水利设施。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">2 5 </span></p>
<p><span style="">9 1 5 4 3 </span></p>
<p><span style="">8 7 6 1 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">1</span></p>
<p><span style="">1</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】 本题共有10个测试数据，每个数据的范围如下表所示： 测试数据编号 能否满足要求 N M 1 不能 ≤ 10 ≤ 10 2 不能 ≤ 100 ≤ 100 3 不能 ≤ 500 ≤ 500 4 能 = 1 ≤ 10 5 能 ≤ 10 ≤ 10 6 能 ≤ 100 ≤ 20 7 能 ≤ 100 ≤ 50 8 能 ≤ 100 ≤ 100 9 能 ≤ 200 ≤ 200 10 能 ≤ 500 ≤ 500 对于所有的10个数据，每座城市的海拔高度都不超过10^6</p>
<p> </p>
<p>样例2 说明</p>
<p><img height="152" src="../../../media/image/problem/1066_1.jpg" width="187"></p>
<p> </p>
<p>数据范围</p>
<p><img height="244" src="../../../media/image/problem/1066_2.jpg" width="500"></p>
</div>
</div>