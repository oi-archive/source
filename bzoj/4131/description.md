
# Description

<div class="content"><div>lyp和ld在一个n*m的棋盘上玩翻转棋，游戏棋盘坐标假设为(x, y)，1 ≤ x ≤ n，1 ≤ y ≤ m，这个游戏的游戏的的游戏规则如下：</div>
<div>每次可以操作坐标为 (x, y) 的棋子，要求棋子 (x, y) 必须是黑色，并且同时翻转所有棋子坐标 (x’, y’) 满足 x’≤x, y’≤y。</div>
<div>lyp觉得这样还不够过瘾,于是乎他打算同时玩 k 个这样的游戏, 每次可以对其中某一个游戏进行操作，lyp先手，ld后手，两人轮流进行操作，最后无法进行操作的人判输，现在给你这个游戏的局面，要求输出是先手必胜(“lyp win”)还是后手必胜(“ld win”)。</div>
<div></div>
<p class="NOI2"></p>
<p></p></div>

# Input

<div class="content"><div>第一行一个数T，表示数据组数。</div>
<div>接下来T组数据，对于每一组数据：</div>
<div>接下来一行一个数K，表示有多少个游戏在进行中，</div>
<div>接下来K部分，每部分第一行两个数n,m表示棋盘大小，</div>
<div>接下来n行，每行m个数，0 表示这个棋子是白色，1表示为黑色，第一行第一列代表棋子坐标(1,1)。</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每一组数据，换行输出先手必胜(“lyp win”)还是后手必胜(“ld win”)，输出不包含引号。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
1<br/>
2 2<br/>
1 1<br/>
1 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">lyp win</span></div>

# Hint

<div class="content"><p></p><p>对于所有的测试数据，n*m*K ≤ 105，T ≤ 20。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

