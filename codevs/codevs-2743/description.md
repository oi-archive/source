<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>黑白棋游戏的棋盘由4×4方格阵列构成。棋盘的每一方格中放有1枚棋子，共有8枚白棋子和8枚黑棋子。这16枚棋子的每一种放置方案都构成一个游戏状态。在棋盘上拥有1条公共边的2个方格称为相邻方格。一个方格最多可有4个相邻方格。在玩黑白棋游戏时，每一步可将任何2个相邻方格中棋子互换位置。对于给定的初始游戏状态和目标游戏状态，编程计算从初始游戏状态变化到目标游戏状态的最短着棋序列。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件共有8行。前四行是初始游戏状态，后四行是目标游戏状态。每行4个数分别表示该行放置的棋子颜色。“0”表示白棋；“1”表示黑棋。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">输出文件的第一行是着棋步数n。接下来n行，每行4个数分别表示该步交换棋子的两个相邻方格的位置。例如，abcd表示将棋盘上(a，b)处的棋子与(c，d)处的棋子换位。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1111</p>
<p>0000</p>
<p>1110</p>
<p>0010</p>
<p>1010</p>
<p>0101</p>
<p>1010</p>
<p>0101</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>1222</p>
<p>1424</p>
<p>3242</p>
<p>4344</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>要用状态压缩，康托展开和HASH免谈</p>
</div>
</div>