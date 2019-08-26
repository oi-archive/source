
# Description

<div class="content"><p>一个无向树的度数为 2的结点称为假结点，其它结点称为真结点。一个无向树的简化树<br/>
其结点由原树的全体真结点组成，两个真结点之间有边当且仅当它们在原树中有边，或者在<br/>
原树中有一条联结这两个结点的路，其中间节点全是假结点。两个无向树各自的简化树如果<br/>
同构，即存在结点之间的一一对应，使得在一个树中的任意两个结点之间有边当且仅当它们<br/>
的对应结点在另一个树中有边，则称原来的两个无向树实质同构。给定若干个无向树，将相<br/>
互实质同构的无向树只保留一个其余删除。统计剩下的相互不实质同构的无向树个数，并将<br/>
它们的简化树结点个数从小到大输出。</p></div>

# Input

<div class="content"><p>第一行只有一个正整数 m,后面依次输入m个无向树，每个无向树先用一行输入结点个<br/>
数n，结点就用1到n表示，然后用n-1行输入n-1条无向边，每行有两个 1到n 之间的不<br/>
同的正整数，用一个空格隔开，代表这两个结点之间有无向边。两个树之间无空行。 <br/>
2&lt;=m&lt;=20， 2&lt;=n&lt;=10000</p></div>

# Output

<div class="content"><p>第一行输出一个正整数，即输入中不计实质同构包含无向树的个数 m0(1&lt;=m0&lt;=m)。第<br/>
二行包含不严格递增的 m0个正整数，表示这m0个无向树的简化树结点个数。相邻两数用一<br/>
个空格隔开。</p></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
4<br/>
1 4<br/>
2 4<br/>
3 4<br/>
5<br/>
1 3<br/>
2 3<br/>
3 4<br/>
4 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

