<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这个游戏是这样的：</p>
<p>有一个N×N的棋盘，并将左上角记为（1,1），右下角记为（N，N）游戏开始前有若干个格子被染成了黑色，其余为白色。</p>
<p>如果有两个格子颜色相同并且有一条公共边，称这两个格子同属于一个联通块。例如下图中有5个黑色联通块和3个白色联通块。</p>
<p>在游戏开始后的M秒中，每一秒，都有一个机械手臂将某一个格子染成相反的颜色（黑色-&gt;白色，白色-&gt;黑色），并且向游戏者询问现在黑色联通块和白色联通块之比。若有数目为0的联通块，则输出-1。输出要求为最简比。</p>
<p>菜菜虽然很聪明，但还是算不过来了，于是请你来写个程序计算结果以帮助他取得好成绩。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输出M行，第i行对应第i次操作，按照题目要求输出-1或联通块数目比。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">&nbsp; &nbsp; 输出M行，第i行对应第i次操作，按照题目要求输出-1或联通块数目比。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4/3</p>
<p>5/2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<div>
<p>4/3</p>
<p>5/2</p>
</div>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<div>
<p>对于20%的数据，有0&lt;N，M&lt;=5。</p>
<p>对于100%的数据，有0&lt;N&lt;=200，0&lt;M&lt;=10000。</p>
</div>
</div>
</div>