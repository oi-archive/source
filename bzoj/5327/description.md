
# Description

<div class="content"><div>JYY 最近从朋友那里获得了一本魔法书，现在他正在练习里面的JSOI 魔法。JSOI 魔法施放过程是这样的：有一个</div>
<div>左右各有N和M个点的二分图构成一个魔法阵，左边N个点由0到N - 1标号，右边M个点由0到M - 1标号。初始时这个</div>
<div>二分图已经有了K个连接（每个连接相当于二分图的一条无向边）。施法分为从0 开始编号的若干轮，在第i轮中，</div>
<div>将会添加一条从左边编号为 i mod N 的点到右边编号为 i mod N 的点的连接。这个过程将会一直继续下去直到整</div>
<div>个二分图节点都能通过连接互通（即二分图连通）。此时魔法阵会被激活，JSOI 就会送你一个萌萌哒的Accept！J</div>
<div>YY 想知道对于给定的初始条件，魔法阵激活所需的轮数（即加入的边数）。</div>
<div></div></div>

# Input

<div class="content"><div>第一行三个正整数N、M、K，表示二分图左边、右边的点数和初始的边数。</div>
<div>接下来K行，每行两个整数ui、vi。表示初始时存在从左边标号ui到右边标号vi的一个连接。</div>
<div>1 ≤ N,M ≤ 10^9, 0 ≤ K ≤ 10,000。</div>
<div></div></div>

# Output

<div class="content"><div>输出一个整数，表示一共进行的轮数。JSOI 保证魔法阵一定能被激活。</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 5 2<br/>
1 3<br/>
2 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

