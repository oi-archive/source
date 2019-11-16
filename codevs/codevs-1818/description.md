<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小云和小南两姐妹从小喜欢下象棋，现在作为象棋高手的她们，已经不屑于玩平常的象棋了，于是她们便开始用棋盘和棋子玩各种各样的新游戏。</p>
<p>今天天气晴朗，阳光明媚，她们将在<span style="font-family: 'Times New Roman';">n * m</span><span style="">的棋盘上进行游戏。</span></p>
<p>棋盘上有<span style="font-family: 'Times New Roman';">k</span><span style="">颗棋子和若干有障碍格子，令棋盘左上角格子坐标为</span><span style="font-family: 'Times New Roman';">(1, 1)</span><span style="">，右下角格子坐标为</span><span style="font-family: 'Times New Roman';">(n, m)</span><span style="">，参数</span><span style="font-family: 'Times New Roman';">a</span><span style="">、</span><span style="font-family: 'Times New Roman';">b</span><span style="">规定了所有棋子的走法：在</span><span style="font-family: 'Times New Roman';">(x, y)</span><span style="">的棋子下一步能走到</span><span style="font-family: 'Times New Roman';">(x + a, y + b), (x + a, y - b), (x </span>– a, y + b), (x – a, y – b), (x + b, y + a), (x + b, y - a), (x – b, y + a), (x – b, y – a)<span style="">这八个格子中的一个，棋子任何时候不能跃出棋盘或走到有障碍的格子上。</span></p>
<p>这<span style="font-family: 'Times New Roman';">k</span><span style="">颗棋子是相同的，小云和小南的目标是用最少步数把所有棋子移动到特定格子，要求移动过程中不能出现多颗棋子同时在某一格的情况。</span></p>
<p>她们已经想出步数较少方案，但无法确定这是否为最少步数，所以向作为程序员的你求助。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行五个空格隔开的整数<span style="font-family: 'Times New Roman';">n</span><span style="">、</span><span style="font-family: 'Times New Roman';">m</span><span style="">、</span><span style="font-family: 'Times New Roman';">k</span><span style="">、</span><span style="font-family: 'Times New Roman';">a</span><span style="">以及</span><span style="font-family: 'Times New Roman';">b</span><span style="">；</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">n</span><span style="">行，每行为长度</span><span style="font-family: 'Times New Roman';">m</span><span style="">的字符串，描述棋盘，‘</span><span style="font-family: 'Times New Roman';">.</span><span style="">’表示没有障碍的格子，‘</span><span style="font-family: 'Times New Roman';">*</span><span style="">’表示有障碍的格子</span>；</p>
<p>接下来<span style="font-family: 'Times New Roman';">k</span><span style="">行，每行两个整数</span><span style="font-family: 'Times New Roman';">x</span><span style="">和</span><span style="font-family: 'Times New Roman';">y</span><span style="">，分别表示</span><span style="font-family: 'Times New Roman';">k</span><span style="">颗棋子的初始位置；</span></p>
<p>接下来<span style="font-family: 'Times New Roman';">k</span><span style="">行，每行两个整数</span><span style="font-family: 'Times New Roman';">x</span><span style="">和</span><span style="font-family: 'Times New Roman';">y</span><span style="">，分别表示</span><span style="font-family: 'Times New Roman';">k</span><span style="">颗棋子的目标位置。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="p0">一个整数，为把所有棋子移动到&rsquo;t&rsquo;位置的最少步数，数据保证有解。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>1 8 2 2 0</p>
<p>.......*</p>
<p>1 1</p>
<p>1 3</p>
<p>1 5</p>
<p>1 7</p>

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

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>样例说明</p>
<p>一可行方案如下：第二颗棋子向右跳两步，随后第一颗棋子向右跳两步，共<span style="font-family: 'Times New Roman';">4</span><span style="">步。值得注意的是，第一颗棋子向右跳三步，随后第二颗棋子向右跳一步的方案尽管能把棋子都移动到目标位置，但途中两颗棋子曾经同时在</span><span style="font-family: 'Times New Roman';">(1, 3)</span><span style="">，违反了规则，所以不能选用此方案。</span></p>
<p> </p>
<p>数据范围</p>
<p>其中<span style="font-family: 'Times New Roman';">20%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">n * m </span><span style="">≤ </span><span style="font-family: 'Times New Roman';">20</span><span style="">；</span></p>
<p>另外<span style="font-family: 'Times New Roman';">10%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">n = 1</span><span style="">；</span></p>
<p>对于<span style="font-family: 'Times New Roman';">100%</span><span style="">的数据，</span><span style="font-family: 'Times New Roman';">n</span><span style="">、</span><span style="font-family: 'Times New Roman';">m </span><span style="">≤ </span><span style="font-family: 'Times New Roman';">100</span><span style="">，</span><span style="font-family: 'Times New Roman';">k </span><span style="">≤ </span><span style="font-family: 'Times New Roman';">500</span><span style="">。</span></p>
<p> </p>
</div>
</div>