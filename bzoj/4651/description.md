
# Description

<div class="content"><div>跳蚤国王和蛐蛐国王在玩一个游戏。</div>
<div>他们在一个 n 行 m 列的网格上排兵布阵。其中的 c 个格子中 (0≤c≤nm)，每个格子有一只蛐蛐，其余的格子中，每个格子有一只跳蚤。</div>
<div>我们称占据的格子有公共边的两只跳蚤是相邻的。</div>
<div>我们称两只跳蚤是连通的，当且仅当这两只跳蚤相邻，或存在另一只跳蚤与这两只跳蚤都连通。</div>
<div>现在，蛐蛐国王希望，将某些（0 个，1 个或多个）跳蚤替换成蛐蛐，使得在此之后存在至少两只跳蚤不连通。</div>
<div>例如：我们用图<img src="/source/bzoj/4651/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC8xKDEpLnBuZw==.png" width="50" height="50" alt=""/>表示一只跳蚤，用图<img src="/source/bzoj/4651/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC8yKDEpLnBuZw==.png" width="49" height="50" alt=""/>表示一只蛐蛐，那么图 1 描述了一个 n=4,m=4,c=2的情况。</div>
<div>这种情况下蛐蛐国王可以通过将第 2 行第 2 列，和第 3 行第 3 列的两只跳蚤替换为蛐蛐，从而达成他的希望，如图 2 所示。并且，不存在更优的方案，但是可能存在其他替换 2 只跳蚤的方案。</div>
<div>你需要首先判断蛐蛐国王的希望能否被达成。如果能够达成，你还需要最小化被替换的跳蚤的个数。</div>
<div><img src="/source/bzoj/4651/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC8zLnBuZw==.png" width="271" height="266" alt=""/> <img src="/source/bzoj/4651/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC80LnBuZw==.png" width="271" height="257" alt=""/></div></div>

# Input

<div class="content"><div>每个输入文件包含多组数据。</div>
<div>输入文件的第一行只有一个整数 TT，表示数据的组数。保证 1≤T≤20。</div>
<div>接下来依次输入 TT 组数据，每组数据的第一行包含三个整数 n, m, c。</div>
<div>保证1≤n,m≤10^9,0≤c≤min(nm,105)</div>
<div>接下来 c行，每行包含两个整数 x, y表示第 x 行，第 y 列的格子被一个蛐蛐占据（1≤x≤n,1≤y≤m）每一组数据当中，同一个蛐蛐不会被多次描述。</div>
<div>同一行相邻的整数之间由一个空格隔开。</div>
<div>1≤n,m≤10^9, 0≤c≤nm, 1≤x≤n, 1≤y≤m</div>
<div>1≤T≤20。我们记 ∑c为某个测试点中，其 T 组输入数据的所有 c 的总和,∑c≤10^5</div>
<div></div></div>

# Output

<div class="content"><div>对于每一组数据依次输出一行答案。</div>
<div>如果这组数据中，蛐蛐国王的希望不能被达成，输出-1。否则，输出被替换的跳蚤的个数的最小值</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
4 4 2<br/>
1 1<br/>
4 4<br/>
2 3 1<br/>
1 2<br/>
2 2 2<br/>
1 1<br/>
2 2<br/>
1 1 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
0<br/>
-1<br/>
explanation<br/>
第一组数据就是问题描述中的例子。<br/>
对于第二组数据，可以将第 2 行第 2 列的一只跳蚤替换为蛐蛐，从而使得存在两只跳蚤不连通<br/>
并且不存在更优的方案。<br/>
对于第三组数据，最初已经存在两只跳蚤不连通，故不需要再进行替换。<br/>
对于第四组数据，由于最多只有一只跳蚤，所以无论如何替换都不能存在两只跳蚤不连通</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

