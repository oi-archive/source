
# Description

<div class="content"><div>在Star的不懈努力下，终于建成了一个含有N个结点的情报网络。这N个结点通过N - 1条联络边两两相连，每条联</div>
<div>络边有一个特征值w。每当有情报传递时，它必然是在一对点之间展开的（起末点交换视为一种），其传递的途径</div>
<div>为情报网络上的简单路径；也就是说，在N个结点的情报网络中共有C(N, 2)种不同的情报传递途径。对于确定的情</div>
<div>报传递途径，它的特征值为它所经过的每条边的特征值的最大公约数。Star知道，特征值为1的情报传递途径是危</div>
<div>险的，并且在整个网络运转的过程中，会发生Q次某条边特征值改变的情况。他想分别计算出这Q + 1个局面（含初</div>
<div>始局面）中的危险途径个数</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行一个整数N；</div>
<div>以下N - 1行每行三个整数u、v、w表示在结点u、v之间存在一条特征值为w的边；</div>
<div>接下来一行一个整数Q；</div>
<div>以下Q行每行两个整数k、x，表示将读入的第k条边（下标从1开始）的特征值改为x。</div>
<div>N ≤ 100000，Q ≤ 100，1 ≤ w、x ≤ 10^6</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>输出Q + 1行，每行一个整数</div>
<div>依次表示初始局面、第1次修改后的局面、第2次修改后的局面……第Q次修改后的局面所对应的危险途径个数。</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">6<br/>
2 1 3<br/>
2 3 2<br/>
4 1 7<br/>
2 5 3<br/>
6 3 9<br/>
4<br/>
1 6<br/>
1 9<br/>
4 3<br/>
2 9</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
8<br/>
9<br/>
9<br/>
4</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

