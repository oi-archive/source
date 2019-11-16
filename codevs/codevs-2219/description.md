<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>1944年，特种兵麦克接到国防部的命令，要求立即赶赴太平洋上的一个孤岛，营救被敌军俘虏的大兵瑞恩。瑞恩被关押在一个迷宫里，迷宫地形复杂，但是幸好麦克得到了迷宫的地形图。</p>
<p>迷宫的外形是一个长方形，其在南北方向被划分为N行，在东西方向被划分为M列，于是整个迷宫被划分为N*M个单元。我们用一个有序数对（单元的行号，单元的列号）来表示单元位置。南北或东西方向相邻的两个单元之间可以互通，或者存在一扇锁着的门，又或者存在一堵不可逾越的墙。迷宫中有一些单元存放着钥匙，并且所有的门被分为P类，打开同一类的门的钥匙相同，打开不同类的门的钥匙不同。</p>
<p>大兵瑞恩被关押在迷宫的东南角，即（N,M）单元里，并已经昏迷。迷宫只有一个入口，在西北角，也就是说，麦克可以直接进入(1,1)单元。另外，麦克从一个单元移动到另一个相邻单元的时间为1，拿取所在单元的钥匙的时间以及用钥匙开门的时间忽略不计。</p>
<p>你的任务是帮助麦克以最快的方式抵达瑞恩所在单元，营救大兵瑞恩。</p>

<img src="/source/codevs/codevs-2219/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yMjE5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMjIxOS5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是三个整数，依次表示N,M,P的值；</p>
<p>第二行是一个整数K，表示迷宫中门和墙的总个数；</p>
<p>第I+2行（1&lt;=I&lt;=K），有5个整数，依次为Xi1,Yi1,Xi2,Yi2,Gi：</p>
<p>当Gi&gt;=1时，表示(Xi1,Yi1)单元与(Xi2,Yi2)单元之间有一扇第Gi类的门，当Gi=0时，表示(Xi1,Yi1)单元与(Xi2,Yi2)单元之间有一堵不可逾越的墙；</p>
<p>（其中，|Xi1-Xi2|+|Yi1-Yi2|=1，0&lt;=Gi&lt;=P）</p>
<p>第K+3行是一个整数S，表示迷宫中存放的钥匙总数；</p>
<p>第K+3+J行(1&lt;=J&lt;=S)，有3个整数，依次为Xi1,Yi1,Qi：表示第J把钥匙存放在(Xi1,Yi1)单元里，并且第J把钥匙是用来开启第Qi类门的。（其中1&lt;=Qi&lt;=P）</p>
<p>注意：输入数据中同一行各相邻整数之间用一个空格分隔。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件只包含一个整数T，表示麦克营救到大兵瑞恩的最短时间的值，若不存在可行的营救方案则输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4 9</p>
<p>9</p>
<p>1 2 1 3 2</p>
<p>1 2 2 2 0</p>
<p>2 1 2 2 0</p>
<p>2 1 3 1 0</p>
<p>2 3 3 3 0</p>
<p>2 4 3 4 1</p>
<p>3 2 3 3 0</p>
<p>3 3 4 3 0</p>
<p>4 3 4 4 0</p>
<p>2</p>
<p>2 1 2</p>
<p>4 2 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>14</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>3&lt;=N,M&lt;=15;</p>
<p>1&lt;=P&lt;=10;</p>
</div>
</div>