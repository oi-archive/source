<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这次他玩起了一款名为大海战的地图。该地图共有n位玩家，每位玩家初始位置为f[i]，每单位时间移动s[i]。游戏开始后，所有玩家对位置最靠前的玩家发起攻击(若多名玩家位置并列第一，则攻击序号最小的玩家)，该名玩家被击败出局。之后每过一个单位之间，均经行上述行动，直至所有玩家都出局。</p>
<p>Yh想知道所有玩家的出具顺序，你能帮他完成吗？</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行为一个整数m，表示有m名玩家。</span></p>
<p><span>接下来有m行，分别表示编号为 i（从1到m）的玩家的数据，每行两个整数Fi（0 &lt;= Fi &lt;= 500），Si(0 &lt; Si &lt;= 100)。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0"><span>一行，输出m个数，数字之间用一个空格隔开，表示被攻击出局的玩家的顺序。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>100 1</p>
<p>100 2</p>
<p>3 100</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>1 3 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%数据，m≤1000</p>
<p>对于100%数据，m≤50000</p>
</div>
</div>