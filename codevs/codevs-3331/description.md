<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>我们定义一个大小为n的阶梯图为一个n*n的矩阵在次对角线（含）以下的部分，下图所示是一个大小为5的阶梯图。</p>
<p>    <img height="233" src="/source/codevs/codevs-3331/img/aHR0cDovL2VzcHJlc3NvLmNvZGVmb3JjZXMuY29tLzFhM2QxZDYyNjQzY2EwYWNlN2E4ZmFmYzUyNDA1YTgwYzAzODgwOTkucG5n.png" width="236"></p>
<p>    在阶梯图上有m名运动员。运动员每秒会移动到与自己所处的格子4连通的相邻格子中。竞赛开始前，每名运动员处在阶梯图中的某个格子中，且每名运动员要选择一个次对角线上与起点距离最近的某个格子作为自己的终点。竞赛开始后，运动员会沿着某条最短路径向终点移动，当运动员到达自己的终点后就会停止移动。</p>
<p>    你的任务是，选择尽量多的运动员参赛，并安排好路线，使得在竞赛过程中不会出现两名运动员同时出现在同一格（包括次对角线上的格子）。</p>
<p>    注：以下情况是允许的：在某一秒，一个运动员离开某格，另一个运动员进到该格。</p>
<p>    两个运动员相向而行是不可能出现的：因为他们必须沿最短路径前进。</p>
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
<p>第一行两个整数n，m，表示阶梯图规模和运动员人数。</p>
<p>以下m行，每行两个整数r[i]，c[i]（1 &lt;= r[i],c[i] &lt;= n, n–c[i] &lt; r[i]），表示第i名运动员的起点在第r[i]行第c[i]列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个整数，表示最多可以有多少名运动员参赛，使得不会有两名运动员同时出现在同一格。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>
<p>2 3</p>
<p>3 2</p>
<p>3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>【样例解释】</p>
<p><img height="186" src="/source/codevs/codevs-3331/img/aHR0cDovL2VzcHJlc3NvLmNvZGVmb3JjZXMuY29tLzY5ZDdhNDUzZmJjYjVlYzA0NWE1Y2UxZGE2OWFlMDRhMmFhYzFjZWQucG5n.png" width="187"></p>
<p><img src="/source/codevs/codevs-3331/img/aHR0cDovL2VzcHJlc3NvLmNvZGVmb3JjZXMuY29tLzY5ZDdhNDUzZmJjYjVlYzA0NWE1Y2UxZGE2OWFlMDRhMmFhYzFjZWQucG5n.png"></p>
<p><img src="/source/codevs/codevs-3331/img/aHR0cDovL2VzcHJlc3NvLmNvZGVmb3JjZXMuY29tLzY5ZDdhNDUzZmJjYjVlYzA0NWE1Y2UxZGE2OWFlMDRhMmFhYzFjZWQucG5n.png"></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>    对于30%的数据， 1 &lt;= n, m &lt;= 10</p>
<p>    对于60%的数据， 1 &lt;= n, m &lt;= 1000</p>
<p>    对于100%的数据， 1 &lt;= n, m &lt;= 10^5</p>
<p><br><!--[endif]--></p>
</div>
</div>