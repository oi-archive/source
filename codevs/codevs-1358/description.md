<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这个游戏在一个有10*10个格子的棋盘上进行，初始时棋子位于左上角，终点为右下角，棋盘上每个格子内有一个0到9的数字，每次棋子可以往右方或下方的相邻格子移动，求一条经过数字之和最小且经过0到9的所有数字的合法路径，输出其长度。（经过的数字包括左上角和右下角）</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入包含10行，每行10个数字，以空格隔开，表示棋盘格子上的权值。数据保证存在合法路径。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出所求路径的权值和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>0 1 2 3 4 5 6 7 8 9</p>
<p>1 1 1 1 1 1 1 1 1 0</p>
<p>2 1 1 1 1 1 1 1 1 0</p>
<p>3 1 1 1 1 1 1 1 1 0</p>
<p>4 1 1 1 1 1 1 1 1 0</p>
<p>5 1 1 1 1 1 1 1 1 0</p>
<p>6 1 1 1 1 1 1 1 1 0</p>
<p>7 1 1 1 1 1 1 1 1 0</p>
<p>8 1 1 1 1 1 1 1 1 0</p>
<p>9 1 1 1 1 1 1 1 1 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>50</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】</p>
<p>先一直向右走到第一行末尾，再竖直向下走位最优路径。</p>
</div>
</div>