<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在一个 n*m 的棋盘上，每个格子有一个权值，初始时，在某个格子的顶点<br>处一只面朝北的蚂蚁，我们只知道它的行走路线是如何转弯，却不知道每次转弯<br>前走了多长。蚂蚁转弯是有一定特点的，即它的转弯序列一定是如下的形式：<br>右转，右转，左转，左转，右转，右转…左转，左转，右转，右转，右转。<br>即两次右转和两次左转交替出现的形式，最后两次右转（最后两次一定是<br>右转）后再多加一次右转。我们还知道，蚂蚁不会在同一个位置连续旋转两次，<br>并且蚂蚁行走的路径除了起点以外，不会到达同一个点多次，它最后一定是回<br>到起点然后结束自己的行程，而且蚂蚁只会在棋盘格子的顶点处转弯。<br>设 k为蚂蚁左转的次数除以2，当k=0 时，蚂蚁可能行走的路径如下图</p>
<p>转弯序列为：右转，右转，右转。<br>当 k=1 时，蚂蚁可能行走的路径如下图<br><br></p>
<p>转弯序列为：右转，右转，左转，左转，右转，右转，右转。<br>现在已知棋盘大小、每个格子的权值以及左转次数/2 的值，问蚂蚁走出<br>的路径围出的封闭图形，权值之和最大可能是多少。</p>
<p> </p>
<p> </p>

<img src="/source/codevs/codevs-1617/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xNjE3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTYxNy5qcGc=.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>在输入文件ant.in 中，第一行三个数n,m,k。意义如题目描述。<br>接下来一个n 行m 列的整数矩阵，表示棋盘。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一个数，表示蚂蚁所走路径围出的图形可能的最大权<br />值和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 5 2<br>-1 -1 -1 -1 -1<br>-1 -1 -1 -1 -1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>-8</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】<br>除了第一行的第二个和第一行的第四个都要围起来才至少合法。<br>【数据规模与约定】<br>10%的数据所有格子中权值均非负<br>另20%的数据n=2<br>另30%的数据k=0<br>100%的数据1≤n≤100,1≤m≤100,0≤k≤10 保证存在合法路径，数据有梯度，格子中每个元素的值绝对值不超过 10000</p>
</div>
</div>