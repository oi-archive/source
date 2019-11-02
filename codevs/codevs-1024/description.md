<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>       小松所在的PK大学校园又称作燕园，是一个十分美丽的校园。有博雅塔，未名湖，亚洲最大的高校图书馆，人称“一塔湖图”。但是由于燕园的历史比较悠久，所以很多的老房子都要不断地维修（就像故宫现在在维修一样），这导致了燕园中的一些路是禁止通行的。</p>
<p>       十分有趣的是，整个燕园的形状是南北朝向的一个四边形，而燕园的建筑格局也十分有规则。你可以假设他被<em>n</em>条横向的路和<em>m</em>条纵向的路分割成了大大小小的很多块区域。禁止通行的那些路正好在两个<strong>相邻</strong>的交叉路口之间。小松十分想知道，他要从他宿舍所在的A路口到达图书馆所在的B路口需要多少时间（他只能沿着能够通行的道路行走，并假设小松走1单位长度需要1单位的时间）？你能帮助他吗？（不要误会小松如此勤奋要去图书馆看书，小松去图书馆的主要原因是那里是全校PPMM最多的地方）。</p>
<p>       另外要说的是，燕园中还有很多的地方是湖。所以湖所占的区域也是不能通行的。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>       输入文件的第一行包含4个整数<em>n</em>（1<em>≤n</em><em>≤</em>10），<em>m</em>（1<em>≤m</em><em>≤</em>10），<em>t</em>（1<em>≤t</em><em>≤</em>100），<em>k</em>（1<em>≤k</em><em>≤</em>10）。分别表示燕园中有<em>n</em>条纵向的路和<em>m</em>条横向的路，t条不能通行的路，还有<em>k</em>个湖。接下来的一行有<em>n</em>个整数<em>a</em>1<em>..an</em>。<em>ai</em>（0<em>≤</em><em>ai</em><em>≤</em>100）表示从西往东第<em>i</em>条纵向向路离燕园最西端的距离；再接下来的一行有<em>m</em>个整数<em>b</em>1<em>..bm</em>。<em>bi</em>（0<em>≤bi</em><em>≤</em>100）表示从南往北第<em>i</em>条横向路离燕园最南端的距离；再接下来<em>k</em>行，每行四个整数<em>x</em>1，<em>x</em>2，<em>y</em>1，<em>y</em>2表示由西向东的第<em>x</em>1条路到第<em>x</em>2条路和由南向北的第<em>y</em>1条路到第<em>y</em>2条路之间是一个湖。<span style="text-decoration: underline;">要注意的是湖的边缘是可以行走的，湖也可能有重叠，如果两个湖接壤的话，接壤的部分也是可以行走的</span>；再接下来t行，每行4个整数<em>x</em>1，<em>y</em>1，<em>x</em>2，<em>y</em>2，表示路口（<em>x</em>1，<em>y</em>1）和（<em>x</em>2，<em>y</em>2）之间的路是静止通行的，你可以认定该两个路口一定是相邻的；最后一行包含4个整数<em>x</em>1，<em>y</em>1，<em>x</em>2，<em>y</em>2，表示小松所在的路口A（<em>x</em>1，<em>y</em>1）和图书馆所在的路口B（<em>x</em>2，<em>y</em>2）。</p>
<p>注：路口（<em>x</em>，<em>y</em>）表示由西向东的第<em>x</em>条纵向路和由南向北的第<em>y</em>条横向路的交叉口。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出包括一个整数，表示小松最少需要花费的时间。保证不会出现无解的情况。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4 2 1</p>
<p>0 1 3 4</p>
<p>0 1 3 4</p>
<p>2 4 2 4</p>
<p>2 2 3 2</p>
<p>2 4 3 4</p>
<p>1 3 4 4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>