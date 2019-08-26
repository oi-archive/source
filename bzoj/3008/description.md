
# Description

<div class="content"><div>小云和小南两姐妹从小喜欢下象棋，现在作为象棋高手的她们，已经不屑于玩平常的象棋了，于是她们便开始用棋</div>
<div>盘和棋子玩各种各样的新游戏。今天天气晴朗，阳光明媚，她们将在n * m的棋盘上进行游戏。棋盘上有k颗棋子和</div>
<div>若干有障碍格子，令棋盘左上角格子坐标为(1, 1)，右下角格子坐标为(n, m)，参数a、b规定了所有棋子的走法：</div>
<div>在(x, y)的棋子下一步能走到(x + a, y + b), (x + a, y - b), (x – a, y + b), (x – a, y – b), (x + b,</div>
<div> y + a), (x + b, y - a), (x – b, y + a), (x – b, y – a)这八个格子中的一个，棋子任何时候不能跃出棋</div>
<div>盘或走到有障碍的格子上。这k颗棋子是相同的，小云和小南的目标是用最少步数把所有棋子移动到特定格子，要</div>
<div>求移动过程中不能出现多颗棋子同时在某一格的情况。她们已经想出步数较少方案，但无法确定这是否为最少步数</div>
<div>，所以向作为程序员的你求助。</div></div>

# Input

<div class="content"><div>第一行五个空格隔开的整数n、m、k、a以及b；</div>
<div>接下来n行，每行为长度m的字符串，描述棋盘，‘.’表示没有障碍的格子，‘*’表示有障碍的格子；</div>
<div>接下来k行，每行两个整数x和y，分别表示k颗棋子的初始位置；</div>
<div>接下来k行，每行两个整数x和y，分别表示k颗棋子的目标位置。</div>
<div>n、m ≤ 100，k ≤ 500</div></div>

# Output

<div class="content"><p>一个整数，为把所有棋子移动到’t’位置的最少步数，数据保证有解。</p></div>

# Sample Input

<div class="content"><span class="sampledata">1 8 2 2 0<br/>
.......*<br/>
1 1<br/>
1 3<br/>
1 5<br/>
1 7<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
 <br/>
样例说明一可行方案如下：第二颗棋子向右跳两步，随后第一颗棋子向右跳两步，共4步。值得注意的是，第一颗<br/>
棋子向右跳三步，随后第二颗棋子向右跳一步的方案尽管能把棋子都移动到目标位置，但途中两颗棋子曾经同时在<br/>
(1, 3)，违反了规则，所以不能选用此方案。</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

