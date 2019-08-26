
# Description

<div class="content"><div>给定一个n个点m条边的无向连通图，保证每条边最多属于一个环。两个人在这张图上玩游戏，一开始他们会在某个节点放一个棋子，然后依次移动这个棋子，已经走过的边不能再走，谁不能移动谁就输了。请求出所有先手必胜的游戏开始时放棋子的位置。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(3&lt;=n,m&lt;=500000)，表示点数和边数。</div>
<div>接下来m行每行包含两个正整数a,b(1&lt;=a,b&lt;=n,a!=b)，表示a点到b点之间有一条无向边。</div>
<p></p></div>

# Output

<div class="content"><div>包含n行，对于第i行，如果在i点放棋子先手必胜，输出1，否则输出2。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6 7<br/>
1 2<br/>
2 3<br/>
3 1<br/>
3 4<br/>
4 5<br/>
5 6<br/>
6 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
1<br/>
1<br/>
2<br/>
1<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

