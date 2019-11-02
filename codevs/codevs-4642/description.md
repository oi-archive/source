<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>还记得童年时和同桌玩的井字游戏吗？一个玩家选择X或者O作为自己的棋子，两个人一人下一步，只要先形成三个连成一列或者三个连成一行或者三个连成一个对角线的情况就能获得胜利。输入时，先输入一个数n（0&lt;n&lt;=9)，代表接下来有n行的下棋步骤，从第2行到n+1行，每一行有两个整数row和column分别代表行数和列数，还有一个字符（X或者O），代表下的是什么棋。以最先下棋的玩家为player1，另一个玩家为player2.对于每一次下棋步骤，输出下完这一步后的游戏状态：未完成、平局、玩家1胜利、玩家2胜利（unfinished、draw、player1won、player2won）。</p><p>注意：</p><ol style=""><li><p>同桌可能耍赖，你赢了他还继续下，不过这时候的游戏状态也是你赢哦。</p></li><li><p>只要数据的最后一步输入后还没分出胜负就算平局，例如输入的n=2，无论如何都是平局，故输入第一步后输出unfinished，输入第二步后输出draw。<br></p></li></ol>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入时，先输入一个数n（0&lt;n&lt;=9)，代表接下来有n行的下棋步骤，从第2行到n-1行，每一行有两个整数row和column分别代表行数和列数，还有一个字符（X或者O），代表下的是什么棋。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于每一次下棋步骤，输出下完这一步后的游戏状态：未完成、平局、玩家1胜利、玩家2胜利（unfinished、draw、player1won、player2won）。</p><p>注意：</p><ol class=" list-paddingleft-2" style="list-style-type: decimal;"><li><p>同桌可能耍赖，你赢了他还继续下，不过这时候的游戏状态也是你赢哦。</p></li><li><p>只要数据的最后一步输入后还没分出胜负就算平局，例如输入的n=2，无论如何都是平局，故输入第一步后输出unfinished，输入第二步后输出draw。</p></li></ol><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>  样例1：  </p><pre>9
1 1 X
2 2 O
1 2 X
1 3 O
3 1 X
2 1 O
2 3 X
3 2 O
3 3 X</pre><p>样例2：</p><pre>8
2 2 X
2 1 O
3 3 X
1 1 O
1 3 X
1 2 O
3 1 X
2 3 O</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   样例1输出：<br></p><pre>unfinished
unfinished
unfinished
unfinished
unfinished
unfinished
unfinished
unfinished
draw</pre><p>样例2输出：</p><pre>unfinished
unfinished
unfinished
unfinished
unfinished
unfinished
player1 won
player1 won</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>n（0&lt;n&lt;=9)<br></p>
</div>
</div>