<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>a180285幸运地被选作了地球到喵星球的留学生，其实是作为特工去调查喵星人是否有侵略地球的企图。喵星人果然打算入侵地球！从a180285口中得到确切消息之后，地球防御小组成员决定制定反侵略计划。 <br>喵星到地球的一段必经之路可以看作 n*m的格点，喵星人将会从地图上的S位置出发，目的地是地球的入口T。为了抵抗喵星人的入侵，地球防御小组打算在地图的格点上放置一些炮塔（最多放置 K个），炮塔攻击周围的 8 个方向（8 个方向分别是：东，南，西，北，东北，西北，东南，西南）（如下左图所示，中间格子的炮塔可以攻击周围的八个格子）。此外地球防御小组还可以在地图上放置无限多个障碍，使得喵星人无法从有障碍的格子经过。</p>
<p>作为地球防御小组的一员，请你为喵星人布阵，使得喵星人受到的伤害最大。注意如果<br>有多条从S 到T 的路径，喵星人会选择伤害最小的一条。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行为三个整数 n，m，K，分别表示地图的长和宽，以及最多能放置的炮塔数量。 <br>接下来的n行，每行包含m个字符，‘#’表示地图上原有的障碍，‘.’表示该处为空地，数据保证在原地图上存在S 到T 的路径。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出在合理布阵下，喵星人采取最优策略后，会受到的最大伤害。 <br /> 注意必须保证在布阵结束后喵星人仍然可以沿一条或以上的路径从起点S到达终点T，否则他们组织更大规模的侵略。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 1 <br>S.T <br>... <br>...</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，保证： <br>1&lt;=N, M&lt;=6<br> <br>对于100%的数据，保证： <br>1&lt;=N&lt;=6<br>， <br>1&lt;=M&lt;=20<br> <br>1&lt;=K&lt;=15</p>
<p><br>且从S 到T 的路径必定存在</p>
</div>
</div>