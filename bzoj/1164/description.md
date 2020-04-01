
# Description

<div class="content"><div>一个n*n的棋盘，每个格子要么是黑色要么是白色。白格子是游戏区域，黑格子表示障碍。指定两个格子AB，分别</div>
<div>是先手方和后手方的起始格子。A和B这两格子不重合。游戏中，双方轮流操作。每次操作，玩家向上下左右四个格</div>
<div>子之一走一步，但不能走进黑色格子。有一种特殊情况，当一方玩家，恰好走到当前对方所在的格子里，他就可以</div>
<div>再走一步（不必是同一方向），“跳过对手”。胜负的判定是这样的，若有一方走进对方的起始格子，就算获胜，</div>
<div>即使是跳过对方，也算获胜。输入一个棋盘和双方开始位置，判定胜负归属。</div></div>

# Input

<div class="content"><div>第一行输入数据组数.在[1,10]之间</div>
<div>下面的数据用于描述每种对局,其开始给出棋盘的大小.在[2,300]</div></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
4<br/>
A...<br/>
.#..<br/>
....<br/>
...B<br/>
4<br/>
A...<br/>
....<br/>
..#.<br/>
...B</span></div>

# Sample Output

<div class="content"><span class="sampledata">B<br/>
A</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">详见曹钦翔论文</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

