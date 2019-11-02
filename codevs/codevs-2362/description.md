<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>刘先生最近在学习国际象棋，使用一个叫”jloi-08”的游戏软件。在这个游戏里，不但可以和电脑普通地对弈，还可以学习著名的棋局，还有针对初学者的规则指导等丰富功能。但是…大小却要1.4G T_T。</p>
<p> </p>
<p>言归正传，在这个软件里，为了让玩家更好地理解和运用各个棋子，有很多趣味的游戏，比如以下就是一个：</p>
<p>给出一个棋盘和一些棋子，让你把这些棋子摆放在棋盘上，使得两两不互相攻击。你的得分由你摆放上去的棋子的个数与种类有关。</p>
<p> </p>
<p>这个游戏很复杂，刘先生老是玩不到高分。于是电脑便降低了难度，替刘先生摆上了一些棋子，最后只给你任意多个bishop(教主)。</p>
<p> </p>
<p>现在刘先生便要考一考你，在电脑给出的这张棋盘上，最多能放几个bishop。</p>
<p> </p>
<p>国际象棋中一共有6种棋子：</p>
<p>king     (国王)</p>
<p>queen   (皇后)</p>
<p>bishop  (教主)</p>
<p>knight  (骑士)</p>
<p>rook    (车)</p>
<p>pawn   (步兵)</p>
<p> </p>
<p>queen和knight不用说了；rook攻击水平和垂直两条线上的所有格子；pawn攻击前方两条斜线方向各一格；king攻击周围8个方向各1格；bishop攻击两条对角线上的所有格子。</p>
<p> </p>
<p>除knight以外，所有棋子的攻击范围均会被别的棋子所阻挡。(“前方”指x递增的方向，x行y列)</p>
<p> </p>
<p>可惜的是这个软件也不是顶优秀，给出的棋盘上的棋子可能互相会攻击，不过你不用理会这些，你只要保证你摆放的bishop不与它们以及不互相攻击就可以了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是2个整数x, y　(1&lt;=x,y&lt;=1024)，</p>
<p>下面的x行每行y个字符表示棋盘，</p>
<p> </p>
<p>其中：K – king, Q – queen, B – bishop, N – knight, R – rook, P – pawn, “.” – blank.</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行一个数，表示最多能够摆放的bishop的个数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3</p>
<p>..N</p>
<p>...</p>
<p>...</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1&lt;=x,y&lt;=1024</p>
</div>
</div>