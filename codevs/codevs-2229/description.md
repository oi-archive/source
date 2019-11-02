<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在台湾宜兰的一个小乡镇里，小学生之间流传着一个称为“新井字”的双人对弈游戏。这种游戏使用的道具是一个“井”字形的棋盘( 如图所示) ，和12个棋子。游戏开始时，棋盘上每一个标示英文字母的地方，都可以随机决定要不要摆放一个棋子( 但是当然不能整个棋盘都不放棋子)。游戏进行的规则是由两个游戏者轮流取走棋盘上的棋子，每人每次必须取走棋盘上任意1 个或2 个相邻( 棋盘上有直线相连) 的棋子，而被迫取走最后一个棋子的人算输，另一位游戏者则得胜。</p>
<p> <img height="173" src="../../../media/image/problem/2229.png" width="241"></p>
<p>其实如果仔细思考，可以证明不管游戏开始时的棋盘状态( 简称起始状态) 如何，先开始取棋子的人（先手）与其对手（后手）二人中必定恰有一人，只要他每次都用对自己最有利的方法，最后一定会得胜。举例来说，若起始状态中只有A 、B 、F 处有棋子，则先手不管取走哪一个棋子，后手只要再移除一个棋子，就可以逼迫先手去取最后一个棋子，因此后手有百分之百得胜的把握，我们可以说“这个起始状态是后手有利”。再举另一个例子，若起始状态只有A 、C 、D处有棋子，则先手只要懂得先取走A 与D 处相邻的兩个棋子，就可以迫使后手去取最后一个棋子，因此先手就有百分之百得胜的把握，我们可以说“这个起始状态是先手有利”。本题就是要请你写一个程序，来判断在不同的起始状态下到底是先手还是后手有利。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行只含一个整数n (1&lt;=n&lt;=10) ，告诉你总共有多少个起始状态需要判断。接下来的n 行，每一行表示一种起始状态。起始状态是以连续12个1 或0的数字来依序表示A 到L 的位置上有没有棋子，1 代表该位置有棋子，0 表示该位置没有棋子。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>对于输入的每一种起始状态，若该起始状态为对先手有利，你的程序必须输出一个字符1，若对后手有利，则必须输出一个字符0。因为输入总共有n 个起始状态，因此总共必须输出n 个字符在同一行，且这些字符之间不需留空白。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>样例1：</p>
<p>1</p>
<p>110001000000</p>
<p> </p>
<p>样例2：</p>
<p>2</p>
<p>101100000000</p>
<p>001100110010</p>
<p> </p>
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
<p>样例1：</p>
<p>0</p>
<p> </p>
<p>样例2：</p>
<p>11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=n&lt;=10</p>
<p>TW一百学年度全国高级中学咨询学科能力竞赛决赛3</p>
</div>
</div>