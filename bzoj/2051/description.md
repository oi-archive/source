
# Description

<div class="content">给出一个N个结点的树，每条边有一个正整数权值，定义两个结点的距离为连接这两个结点路径上边权的和。对于每个结点i，它到其他N-1个结点都有一个距离，将这些距离从小到大排序，输出第K个距离。
</div>

# Input

<div class="content">输入文件总共N行。第一行有两个正整数N和K。下面N-1行每行描述树的一条边（保证这些边可以构成一棵树），每行三个正整数u、v、w，表示从结点u到结点v有一条权值为w的边。
输入文件保证：N &lt;= 50000, K &lt; N, u &lt;= N, v &lt;= N, w &lt;= 10000。
</div>

# Output

<div class="content">输出文件总共N行，每行一个正整数，第i行的数对于结点i的答案。

</div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
1 2 2<br/>
1 3 4<br/>
1 4 3<br/>
3 5 1<br/>
3 6 2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
6<br/>
4<br/>
7<br/>
5<br/>
6<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=陶文博">陶文博</a></p></div>

