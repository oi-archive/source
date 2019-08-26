
# Description

<div class="content"><p>给定一棵n个点的树，树上每条边的长度都为1，第i个点的权值为a[i]。<br/>
Byteasar想要走遍这整棵树，他会按照某个1到n的全排列b走n-1次，第i次他会从b[i]点走到b[i+1]点，并且这一次的步伐大小为c[i]。<br/>
对于一次行走，假设起点为x，终点为y，步伐为k，那么Byteasar会从x开始，每步往前走k步，如果最后不足k步就能到达y，那么他会一步走到y。<br/>
请帮助Byteasar统计出每一次行走时经过的所有点的权值和。</p></div>

# Input

<div class="content"><p>第一行包含一个正整数n(2&lt;=n&lt;=50000)。表示节点的个数。<br/>
第二行包含n个正整数，其中第i个数为a[i](1&lt;=a[i]&lt;=10000)，分别表示每个点的权值。<br/>
接下来n-1行，每行包含两个正整数u,v(1&lt;=u,v&lt;=n)，表示u与v之间有一条边。<br/>
接下来一行包含n个互不相同的正整数，其中第i个数为b[i](1&lt;=b[i]&lt;=n)，表示行走路线。<br/>
接下来一行包含n-1个正整数，其中第i个数为c[i](1&lt;=c[i]&lt;n)，表示每次行走的步伐大小。</p></div>

# Output

<div class="content"><p>包含n-1行，每行一个正整数，依次输出每次行走时经过的所有点的权值和</p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2 3 4 5<br/>
1 2<br/>
2 3<br/>
3 4<br/>
3 5<br/>
4 1 5 2 3<br/>
1 3 1 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">10<br/>
6<br/>
10<br/>
5</span></div>

# Hint

<div class="content"><p></p><p>鸣谢Claris</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Claris">鸣谢Claris</a></p></div>

