
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">一个n*n（n&gt;=2）棋盘上有黑白棋子各一枚。游戏者A和B轮流移动棋子，A先走。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>A的移动规则：只能移动白棋子。可以往上下左右四个方向之一移动一格。</span></div>
<div style="margin: 0cm 0cm 0pt 21pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>B的移动规则：只能移动黑棋子。可以往上下左右四个方向之一移动一格或者两格。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">和通常的“吃子”规则一样，当某游戏者把自己的棋子移动到对方棋子所在的格子时，他就赢了。两个游戏者都很聪明，当可以获胜时会尽快获胜，只能输掉的时候会尽量拖延时间。你的任务是判断谁会赢，需要多少回合。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">比如n=2，白棋子在(1,1)，黑棋子在(2,2)，那么虽然A有两种走法，第二个回合B总能取胜。</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">输入仅一行，包含五个整数n, r1, c1, r2, c2，即棋盘大小和棋子位置。白色棋子在(r1,c1)，黑色棋子在(r2,c2)（1&lt;=r1,c1,r2,c2&lt;=n）。黑白棋子的位置保证不相同。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">输出仅一行，即游戏结果。如果A获胜，输出WHITE x；如果B获胜，输出BLACK x；如果二者都没有必胜策略，输出DRAW。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 1 1 2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">BLACK 2</span></div>

# Hint

<div class="content"><p></p><p>n&lt;=20</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

