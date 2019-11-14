
# Description

<div class="content"><p></p>
<div>别忘了这是一棵动态树, 每时每刻都是动态的. 小明要求你在这棵树上维护两种事件</div>
<div>事件0:</div>
<div>这棵树长出了一些果子, 即某个子树中的每个节点都会长出K个果子.</div>
<div>事件1:</div>
<div>小明希望你求出几条树枝上的果子数. 一条树枝其实就是一个从某个节点到根的路径的一段. 每次小明会选定一些树枝, 让你求出在这些树枝上的节点的果子数的和. 注意, 树枝之间可能会重合, 这时重合的部分的节点的果子只要算一次.</div>
<div></div></div>

# Input

<div class="content"><div>第一行一个整数n(1&lt;=n&lt;=200,000), 即节点数.</div>
<div>接下来n-1行, 每行两个数字u, v. 表示果子u和果子v之间有一条直接的边. 节点从1开始编号.</div>
<div>在接下来一个整数nQ(1&lt;=nQ&lt;=200,000), 表示事件.</div>
<div>最后nQ行, 每行开头要么是0, 要么是1.</div>
<div>如果是0, 表示这个事件是事件0. 这行接下来的2个整数u, delta表示以u为根的子树中的每个节点长出了delta个果子.</div>
<div>如果是1, 表示这个事件是事件1. 这行接下来一个整数K(1&lt;=K&lt;=5), 表示这次询问涉及K个树枝. 接下来K对整数u_k, v_k, 每个树枝从节点u_k到节点v_k. 由于果子数可能非常多, 请输出这个数模2^31的结果.</div></div>

# Output

<div class="content"><p><font size="4">对于每个事件1, 输出询问的果子数.<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 2<br/>
2 3<br/>
2 4<br/>
1 5<br/>
3<br/>
0 1 1<br/>
0 2 3<br/>
1 2 3 1 1 4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">13<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium"> 1 &lt;= n &lt;= 200,000, 1 &lt;= nQ &lt;= 200,000, K = 5.<br/><br/>
</span></p><br/>
<p><span style="font-size: medium">生成每个树枝的过程是这样的:先在树中随机找一个节点, 然后在这个节点到根的路径上随机选一个节点, 这两个节点就作为树枝的两端.<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

