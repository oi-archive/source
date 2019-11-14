
# Description

<div class="content"><div>小Z最近在玩一个叫做黑白棋的单机小游戏。</div>
<div>这个游戏的规则如下：</div>
<div>（1）棋盘为一个n*m的矩阵，每个格子可能是黑色或白色；</div>
<div>（2）游戏目标是将所有格子变为黑色；</div>
<div>（3）游戏参与者的每次操作是：选出一个白色格子，将它以及它所在行的格子与所</div>
<div>在列的格子全部染成黑色；</div>
<div>（4）当所有的格子都变为黑色时，游戏结束。</div>
<div>完成这个游戏有许多种方案，每种方案可以表示成若干格子的一个序列。若两种方案长度不同或者存在i使得两种</div>
<div>方案中的第i个格子不同，则认为这两种方案不同。由于完成这个游戏的难度系数为0，聪明的小Z自然不满足于此</div>
<div>，他还想知道一共有多少种方案可以完成这个游戏。现在给你这个棋盘的初始状态，请你算一下不同方案的个数。</div>
<div>由于方案可能很多，所以只需要求出答案对1000000007取模后的余数。</div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>每个测试点包含多组测试数据。</div>
<div>第一行，包含一个整数，T，表示数据组数。</div>
<div>接下来依次给出T组数据。</div>
<div>每组数据第一行，包含两个整数，n、m，表示棋盘的大小。</div>
<div>接下来n行，每行一个长度为m的字符串。</div>
<div>其中第i行、第j个字符描述棋盘的第i行第j列的格子。“B”表示为黑色格子，“.”表示为白色格子。</div>
<div> 1≤n,m,T≤20，每个棋盘中的黑色格子不超过 8 个</div>
<div></div>
<div>
<div></div>
</div>
<div>
<div></div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一共包含T行，第i行包含一个整数，表示第i组数据的答案。</div>
<div></div>
<div></div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
2 3<br/>
. . .<br/>
B B .<br/>
4 4<br/>
. . . .<br/>
. . . .<br/>
. . . .<br/>
. . . .</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
576</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

