<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>迷宫可是每个游乐园必不可少的项目，菜菜当然是要尝试一下啦。</p>
<p>这个迷宫比较特殊。与其说是迷宫，倒不如说是一个巨大的格子。游乐园给菜菜发了一张地图，地图上标明了，这个格子由n行m列共n*m个小格子组成。有的格子可以正常走，标为’.’；有的格子有陷阱不能走，标为‘#’；有的格子比较特殊，标为‘*’，可以向周围八个方向可走的格子走一格；目的地标记为‘@’。菜菜从左上角处开始，并且可以按中国象棋中的马和象的方式或者特殊格的八方向来走。如果按照最短的路径到达目的地，则可以获得奖励。</p>
<p>菜菜当然想获得奖励啦，于是就来找你帮忙，请你帮忙计算最少需要多少步。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，两个正整数n，m。</p>
<p>接下来的n行m列描述了地图。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个整数，表示所要走的最小步数。若无法到达目的地则输出-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11 10</p>
<p>..........</p>
<p>....#.....</p>
<p>..........</p>
<p>...#.*....</p>
<p>.......*..</p>
<p>..#..#...@</p>
<p>*.........</p>
<p>...#...#..</p>
<p>.....*....</p>
<p>...#......</p>
<p>..*....*..</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>13</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于20%的数据，保证0＜n,m≤20</p>
<p>对于100%的数据，保证0＜n,m≤200</p>
</div>
</div>