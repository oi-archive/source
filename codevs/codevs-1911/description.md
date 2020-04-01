<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>1944 年，特种兵麦克接到国防部的命令，要求立即赶赴太平洋上的一个孤岛，营救被<br>敌军俘虏的大兵瑞恩。瑞恩被关押在一个迷宫里，迷宫地形复杂，但幸好麦克得到了迷宫的<br>地形图。迷宫的外形是一个长方形，其南北方向被划分为N 行，东西方向被划分为M列，<br>于是整个迷宫被划分为N×M 个单元。每一个单元的位置可用一个有序数对(单元的行号，<br>单元的列号)来表示。南北或东西方向相邻的2 个单元之间可能互通，也可能有一扇锁着的<br>门，或者是一堵不可逾越的墙。迷宫中有一些单元存放着钥匙，并且所有的门被分成P类，<br>打开同一类的门的钥匙相同，不同类门的钥匙不同。</p>
<p>大兵瑞恩被关押在迷宫的东南角，即(N，M)单元里，并已经昏迷。迷宫只有一个入口，<br>在西北角。也就是说，麦克可以直接进入(1，1)单元。另外，麦克从一个单元移动到另一个<br>相邻单元的时间为1，拿取所在单元的钥匙的时间以及用钥匙开门的时间可忽略不计。<br>«编程任务：<br>试设计一个算法，帮助麦克以最快的方式到达瑞恩所在单元，营救大兵瑞恩。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第1行有3个整数，分别表示N,M,P的值。第2 行是1<br>个整数K，表示迷宫中门和墙的总数。第I+2 行（1&lt;=I&lt;=K），有5 个整数，依次为<br>Xi1,Yi1,Xi2,Yi2,Gi：<br>当Gi&gt;=1时，表示(Xi1,Yi1)单元与(Xi2,Yi2)单元之间有一扇第Gi类的门，当Gi=0 时，<br>表示(Xi1,Yi1)单元与(Xi2,Yi2)单元之间有一堵不可逾越的墙（其中，|Xi1-Xi2|+|Yi1-Yi2|=1，<br>0&lt;=Gi&lt;=P）。<br>第K+3行是一个整数S，表示迷宫中存放的钥匙总数。<br>第K+3+J 行(1&lt;=J&lt;=S)，有3个整数，依次为Xi1,Yi1,Qi：表示第J 把钥匙存放在(Xi1,Yi1)<br>单元里，并且第J 把钥匙是用来开启第Qi类门的。（其中1&lt;=Qi&lt;=P）。<br>输入数据中同一行各相邻整数之间用一个空格分隔。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>将麦克营救到大兵瑞恩的最短时间的值输出。如果问题无解，则输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 4 9<br>9<br>1 2 1 3 2<br>1 2 2 2 0<br>2 1 2 2 0<br>2 1 3 1 0<br>2 3 3 3 0<br>2 4 3 4 1<br>3 2 3 3 0<br>3 3 4 3 0<br>4 3 4 4 0<br>2<br>2 1 2<br>4 2 1</p>

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

</div>
</div>