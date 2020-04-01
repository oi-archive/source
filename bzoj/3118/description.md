
# Description

<div class="content"><div><span style="font-size: medium">给出一个带权的连通无向图，对于其中的每条边i，在原来边权的基础上，其边权每增加1需要付出的代价为Ai，边权每减少1需要付出的代价为Bi，现在指定该图的一棵生成树，求通过修改边权，使得该生成树成为图的一棵最小生成树，需要付出的最少总代价。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行两个正整数N, M，表示图的点数和边数，点以1~N编号；</span></div>
<div><span style="font-size: medium">接下来M行，每行六个正整数Ui, Vi, Wi, FFi, Ai, Bi，表示一条边(Ui, Vi)权为Wi，在原边权基础上增加1的边权代价为Ai，减少1的边权代价为Bi，FFi若为1则表示该边在指定的生成树中，若为0表示不在。数据保证FF值为1的边刚好组成原图的一棵生成树。两点之间可能有多条不同的边，但没有连接同一点的边。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">输出一个正整数，表示所需付出的最少总代价。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
6 8<br/>
1 2 3 1 4 2<br/>
1 4 2 0 3 4<br/>
2 3 5 1 2 1<br/>
2 4 4 1 3 5<br/>
3 5 2 0 1 3<br/>
3 6 1 0 2 4<br/>
4 5 7 1 3 2<br/>
5 6 5 1 5 4<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
21<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>【Hint】<br/><br/>
样例解释：<br/><br/>
最优方案为：(1, 4)边权加2，代价6；(3, 5)边权加3，代价3；(3, 6)边权加4，代价8；(4, 5)边权减2，代价4；总代价21。<br/><br/>
数据范围：<br/><br/>
1&lt;=N&lt;=300, 1&lt;=M, Wi, Ai, Bi&lt;=1000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Mato_No1提供">Mato_No1提供</a></p></div>

