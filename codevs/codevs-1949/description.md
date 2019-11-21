<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>这些天，兔兔和蛋蛋喜欢上了一种新的棋类游戏。 这个游戏是在一个 n 行 m 列的棋盘上进行的。游戏开始之前，棋盘上有一 个格子是空的，其它的格子中都放置了一枚棋子，棋子或者是黑色，或者是白色。 每一局游戏总是兔兔先操作，之后双方轮流操作，具体操作为：  兔兔每次操作时，选择一枚与空格相邻的白色棋子，将它移进空格。  蛋蛋每次操作时，选择一枚与空格相邻的黑色棋子，将它移进空格。 第一个不能按照规则操作的人输掉游戏。为了描述方便，下面将操作“将第 x 行第 y 列中的棋子移进空格中”记为 M(x,y)。 例如下面是三个游戏的例子。 </p>
<p>最近兔兔总是输掉游戏，而且蛋蛋格外嚣张，于是兔兔想请她的好朋友—— 你——来帮助她。她带来了一局输给蛋蛋的游戏的实录，请你指出这一局游戏中 所有她“犯错误”的地方。 注意：  两个格子相邻当且仅当它们有一条公共边。  兔兔的操作是“犯错误”的，当且仅当，在这次操作前兔兔有必胜策略， 而这次操作后蛋蛋有必胜策略。 </p>

<img src="/source/codevs/codevs-1949/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xOTQ5L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTk0OS5wbmc=.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入的第一行包含两个正整数 n、m。</p>
<p>接下来 n 行描述初始棋盘。其中第 i 行包含 m 个字符，每个字符都是大写英 文字母"X"、大写英文字母"O"或点号"."之一，分别表示对应的棋盘格中有黑色 棋子、有白色棋子和没有棋子。其中点号"."恰好出现一次。</p>
<p>接下来一行包含一个整数 k（1≤k≤1000），表示兔兔和蛋蛋各进行了 k 次操 作。</p>
<p>接下来 2k 行描述一局游戏的过程。其中第 2i – 1 行是兔兔的第 i 次操作（编 号为i的操作），第 2i行是蛋蛋的第i次操作。每个操作使用两个整数x,y来描述， 表示将第 x 行第 y 列中的棋子移进空格中。</p>
<p>输入保证整个棋盘中只有一个格子没有棋子，游戏过程中兔兔和蛋蛋的每个 操作都是合法的，且最后蛋蛋获胜。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件的第一行包含一个整数 r，表示兔兔犯错误的总次数。 接下来 r 行按递增的顺序给出兔兔&ldquo;犯错误&rdquo;的操作编号。其中第 i 行包含 一个整数 ai表示兔兔第 i 个犯错误的操作是他在游戏中的第 ai次操作。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>【输入样例 1】 <br>1 6 XO.OXO 1 1 2 1 1 <br>【输入样例 2】 <br>3 3 XOX O.O XOX 4 2 3 1 3 1 2 1 1 2 1 3 1 3 2 3 3 <br>【输入样例 3】 <br>4 4 OOXX OXXO OO.O XXXO 2 3 2 2 2 1 2 1 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">【输出样例 1】 </span><br>1 1 <br>【输出样例 2】 <br>0 <br>【输出样例 3】 <br>2 1 2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例说明】 <br>样例 1 对应图一中的游戏过程。 样例 2 对应图三中的游戏过程。</p>
<p>【数据规模】</p>
<p>1 ≤n≤ 40， 1 ≤m≤ 40</p>
</div>
</div>