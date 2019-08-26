
# Description

<div class="content"><p>给定一棵有n个点，m个叶子节点的树，其中m个叶子节点分别为1到m号点，每个叶子节点有一个权值r[i]。你需要给剩下n-m个点各指定一个权值，使得树上相邻两个点的权值差的绝对值之和最小。</p></div>

# Input

<div class="content"><p>第一行包含两个正整数n,m(2&lt;=n&lt;=500000，1&lt;=m&lt;=n)，分别表示点数和叶子数。<br/>
接下来n-1行，每行两个正整数u,v(1&lt;=u,v&lt;=n)，表示u与v之间有一条边。<br/>
接下来m行，每行一个正整数，依次为r[1],r[2],...,r[m](1&lt;=r[i]&lt;=500000)，表示每个叶子的权值。</p></div>

# Output

<div class="content"><p>输出一个整数，即树上相邻两个点的权值差的绝对值之和的最小值。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 4<br/>
1 5<br/>
2 5<br/>
3 6<br/>
4 6<br/>
5 6<br/>
5<br/>
10<br/>
20<br/>
40</span></div>

# Sample Output

<div class="content"><span class="sampledata">35</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By Claris">By Claris</a></p></div>

