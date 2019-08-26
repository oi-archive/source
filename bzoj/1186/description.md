
# Description

<div class="content"><div>五子棋是一种流传很广的棋类游戏，在一个15×15的棋盘上，对弈双方执黑白棋子（类似于围棋），执黑子者先下</div>
<div>，凡落下的棋子不能被提起，即不存在挪子和吃子的情况。为了简化问题，假设黑方不存在“禁手”，“禁手”是</div>
<div>五子棋术语，指禁止走棋子的地方。当某选手的棋子在横、竖、45度斜线方向、135度斜线方向之一先出现相连的5</div>
<div>个棋子时，该选手获胜。先考虑轮到黑棋走的一盘残局，请给出黑棋获胜的最少步数和在该步数下能获胜的所有不</div>
<div>同的下一步走法。</div></div>

# Input

<div class="content"><div>共有15行，每行有15个由一个空格隔开的整数。</div>
<div>第i行，第j列的整数记做vij，用vij=0，1，2表示第i行，第j列的位置为空、有1黑子、有1白子，</div>
<div>从左上角开始，按从左至右，自上而下的顺序输入，</div>
<div>即输入的第1行第1列整数v11表示第1行第1列位置的状态，</div>
<div>输入的第15行第15列整数v15，15表示第15行第15列位置的状态。</div></div>

# Output

<div class="content"><div>第一行为两个整数a和b，</div>
<div>其中：a表示黑棋获胜的最少步数，b表示黑棋在a步获胜的所有不同的下一步走法的种数。</div>
<div>从第二行到第b+1行，每行有两个整数，</div>
<div>分别表示黑棋在a步获胜的一种下一步走法落子位置的行数i和列数j，</div>
<div>要求这些走法按照15i+j的大小从小到大排列。</div></div>

# Sample Input

<div class="content"><span class="sampledata">0 0 0 0 0 0 0 0 0 0 0 0 0 0 0<br/>
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0<br/>
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0<br/>
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0<br/>
0 0 0 0 0 0 0 0 0 2 0 0 0 0 0<br/>
0 0 0 0 0 0 0 2 0 2 0 0 0 0 0<br/>
0 0 0 0 0 0 2 1 1 2 0 0 0 0 0<br/>
0 0 0 0 0 0 0 1 2 1 0 0 0 0 0<br/>
0 0 0 0 0 0 2 1 1 1 1 2 0 0 0<br/>
0 0 0 0 0 0 0 1 0 1 0 1 0 0 0<br/>
0 0 0 0 0 0 2 2 0 1 1 0 2 0 0<br/>
0 0 0 0 0 0 0 0 0 2 0 2 0 0 0<br/>
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0<br/>
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0<br/>
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">3 2<br/>
10 9<br/>
10 11</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=数据由SillyHook生成">数据由SillyHook生成</a></p></div>

