<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>oi小组的yh酷爱玩魔兽rpg，每天都会在u9搜索最新的rpg地图。</p>
<p>今天，他找到一张名为《逃出克隆岛》的地图，在这张地图中，有一个n行m列的矩阵，矩阵由’Y’，’C’，’#’，’*’，’P’,5种元素组成。’Y’表示yh的出生位置，C表示克隆岛的出口，’#’表示该处不可通过，’*’表示通过该处需要消耗金币cost,’P’表示传送阵，任意两个传送阵之间可以免费互相传送。由于这仅仅是第一关，yh不想浪费太多的体力，聪明的你能帮他算出从’Y’出发到’C’最少需要消耗多少金币吗？当然，如果yh永远无法到达’C’,请输出” screw you!”以表到yh的不满。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个整数，n,m,表示矩阵有n行m列</p>
<p>接下来为n行m列的矩阵，由’Y’,’C’,’#’,’*’,’P’,组成，含义如题目描述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出1行，表示yh需要花费的最小体力（如果无法到达输出&rdquo;screw&nbsp;you!&rdquo;）。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【样例输入1】</p>
<p>1 3 3</p>
<p>Y*C</p>
<p>【样例输入2】</p>
<p>1 3 2</p>
<p>Y#C</p>
<p>【样例输入3】</p>
<p>1 5 2</p>
<p>YP#PC</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>【样例输出1】</p>
<p>3</p>
<p>【样例输出2】</p>
<p>screw you!</p>
<p>【样例输出3】</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【数据范围】</p>
<p>对于100%的数据，n*m≤5000，传送阵’P’的数量≤500</p>
</div>
</div>