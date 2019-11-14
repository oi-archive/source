<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    奶牛们最近从著名的奶牛玩具制造商Tycow那里，买了一套仿真版彩蛋游戏设备。Bessie把她们玩游戏的草坪划成了N*N单位的矩阵，同时列出了她的K个对手在草地上的位置。然后她拿着这张表来找你，希望你能帮她计算一个数据。</p>
<p>   在这个游戏中，奶牛可以用一把弹珠枪向8个方向（正东、正南、正西、正北、正东北、正东南、正西北、正西南）中的任意一个方向发射子弹。Bessie希望你告诉她，如果她想站在一个可以射到所有对手的格子上，那么她有多少种选择。当然，Bessie可以跟某一个对手站在同一个格子上，在这种情况下，Bessie也能射到这个对手。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：两个用空格隔开的整数：N K</p>
<p>第二至第K+1行：第i+1行有两个以空格隔开的整数R-i和C-i，描述第i头奶牛的位置，表示她站在第R-i行，C-i列。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行：输出一个整数，表示Bessie可以选择的格子数量。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4 3</p>
<p>2 1</p>
<p>2 3</p>
<p>4 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>数据范围</span></p>
<p>1&lt;=N&lt;=500</p>
<p>1&lt;=K&lt;=100 000</p>
<p>样例说明</p>
<p>Bessie可以选择站在一下格子中的任意一个：（2，1），（2，3），（3，2），（4，4），（4，3）.下右图中，Bessie与其他奶牛共同占有的格子被标记为“*”</p>
<p>.   .   .   .                            .   .   .   .</p>
<p>B  .   B  .      =======&gt;    *  .   *  .</p>
<p>.   B   .  .      =======&gt;    .   B  .   .</p>
<p>B  .   B  .                            *  .   B  . </p>
<p>提示：</p>
<p>使用穷举即可。</p>
</div>
</div>