
# Description

<div class="content"><p>你有一个无向连通图，边的总数为偶数。<br/>
设图中有k个奇点（度数为奇数的点），你需要把它们配成k/2个点对（显然k被2整除）。对于每个点对(u,v)，你需要用一条长度为偶数（假设每条边长度为1）的路径将u和v连接。每条路径允许经过重复的点，但不允许经过重复的边。这k/2条路径之间也不能有重复的边。</p></div>

# Input

<div class="content"><p>第一行有两个整数n,m(2&lt;=n,m&lt;=250000)，分别表示点数、边数，m为偶数。<br/>
接下来m行，每行两个整数a,b(1&lt;=a,b&lt;=n,a≠b)，表示a,b间连有一条边。不存在重边。保证奇点的数目不为零。</p></div>

# Output

<div class="content"><p>如果你认为无解就输出NIE。<br/>
设图中有k个奇点，则输出由k/2部分组成，每个部分包含两行：第一行为u,v,l，表示连接的两个点，及路径长度。第二行为空格隔开的l个整数，表示u到v的路径。边按照输入顺序从1到m编号。<br/>
若有多组答案，任意输出其中一个。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 8<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
5 6<br/>
6 1<br/>
1 4<br/>
2 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">样例输出：<br/>
1 5 2<br/>
6 5<br/>
2 4 2<br/>
8 4<br/>
另一种合法输出：<br/>
1 5 6<br/>
1 2 3 7 6 5<br/>
2 4 2<br/>
8 4<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Jcvb">鸣谢Jcvb</a></p></div>

