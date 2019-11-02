<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>Mayan puzzle 是最近流行起来的一个游戏。游戏界面是一个7 行5 列的棋盘，上面堆放</span><br><span>着一些方块，方块不能悬空堆放，即方块必须放在最下面一行，或者放在其他方块之上。游</span><br><span>戏通关是指在规定的步数内消除所有的方块，消除方块的规则如下：</span><br><span>1、每步移动可以且仅可以沿横向（即向左或向右）拖动某一方块一格：当拖动这一方</span><br><span>块时，如果拖动后到达的位置（以下称目标位置）也有方块，那么这两个方块将交换位置（参</span><br><span>见输入输出样例说明中的图6 到图7）；如果目标位置上没有方块，那么被拖动的方块将从</span><br><span>原来的竖列中抽出，并从目标位置上掉落</span><br><img src="/source/codevs/codevs-1136/img/aHR0cDovL3d3dy5ycW5vai5jbi9Qcm9ibGVtUGljL1A2NTYtMTM1ODU1LnBuZw==.png"><br><span>2、任一时刻，如果在一横行或者竖列上有连续三个或者三个以上相同颜色的方块，则</span><br><span>它们将立即被消除（参见图1 到图3）。</span><br><span>注意：</span><br><span>a) 如果同时有多组方块满足消除条件，几组方块会同时被消除（例如下面图4，三个颜</span><br><span>色为1 的方块和三个颜色为2 的方块会同时被消除，最后剩下一个颜色为2 的方块）。</span><br><span>b) 当出现行和列都满足消除条件且行列共享某个方块时，行和列上满足消除条件的所</span><br><span>有方块会被同时消除（例如下面图5 所示的情形，5 个方块会同时被消除）。</span><br><img src="/source/codevs/codevs-1136/img/aHR0cDovL3d3dy5ycW5vai5jbi9Qcm9ibGVtUGljL1A2NTYtMTQwMDAyLnBuZw==.png"><br><span>3、方块消除之后，消除位置之上的方块将掉落，掉落后可能会引起新的方块消除。注</span><br><span>意：掉落的过程中将不会有方块的消除。</span><br><span>上面图 1 到图3 给出了在棋盘上移动一块方块之后棋盘的变化。棋盘的左下角方块的坐</span><br><span>标为（0, 0），将位于（3, 3）的方块向左移动之后，游戏界面从图1 变成图2 所示的状态，</span><br><span>此时在一竖列上有连续三块颜色为4 的方块，满足消除条件，消除连续3 块颜色为4 的方块</span><br><span>后，上方的颜色为3 的方块掉落，形成图3 所示的局面。</span><br><span>【输入输出样例说明】</span><br><img src="/source/codevs/codevs-1136/img/aHR0cDovL3d3dy5ycW5vai5jbi9Qcm9ibGVtUGljL1A2NTYtMTQwMjI5LnBuZw==.png"><br><span>样例输入的游戏局面依次移动的三步是：（2，1）处的方格向</span><br><span>右移动，（3，1）处的方格向右移动，（3，0）处的方格向右移动，最后可以将棋盘上所有方</span><br><span>块消除。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>共6 行。<br>第一行为一个正整数 n，表示要求游戏通关的步数。<br>接下来的 5 行，描述7*5 的游戏界面。每行若干个整数，每两个整数之间用一个空格隔开，每行以一个0 结束，自下向上表示每竖列方块的颜色编号（颜色不多于10 种，从1 开始顺序编号，相同数字表示相同颜色）。<br>输入数据保证初始棋盘中没有可以消除的方块。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>如果有解决方案，输出n 行，每行包含3 个整数x，y，g，表示一次移动，每两个整数之间用一个空格隔开，其中（x，y）表示要移动的方块的坐标，g 表示移动的方向，1 表示向右移动，-1 表示向左移动。注意：多组解时，按照x 为第一关健字，y 为第二关健字，1优先于-1，给出一组字典序最小的解。游戏界面左下角的坐标为（0，0）。<br />如果没有解决方案，输出一行，包含一个整数-1。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3<br>1 0<br>2 1 0<br>2 3 4 0<br>3 1 0<br>2 4 3 4 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2 1 1<br>3 1 1<br>3 0 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>数据范围<br>对于 30%的数据，初始棋盘上的方块都在棋盘的最下面一行；<br>对于 100%的数据，0 &lt; n≤5。</p>
</div>
</div>