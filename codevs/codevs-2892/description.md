<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Sbc玩起了一个低级游戏，就是在给出的一面地图（矩形，n*m个单位大小）中，求由起点到达终点的最少步数!</p>
<p>由于Sbc十分笨，所以他经常呆呆地想策略，为了不让他继续沉迷，你就要编程得出最短路告诉他。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行，n和m</p>
<p>第二到第n+1行是一个n行m列的字符矩阵，“S”代表Sbc所处的位置（即起点），“．”带表空地，“M”代表终点，“*”代表墙(不可穿越)</p>
<p>    注意：矩阵里出现的字母字符不区分大小写!</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行，最少步数</p>
<p>第二行，这条路径的每一步的方向（保证只有一条最短路，ENWN分表代表东南西北）</p>
<p>注意：输出方向必须用大写!</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 6</p>
<p>.*...M</p>
<p>...**.</p>
<p>S*....</p>
<p> </p>

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
<p>NEENEEE</p>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>100%的数据保证，1≤<em>N, M</em>≤30</p>
</div>
</div>