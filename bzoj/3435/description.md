
# Description

<div class="content"><p><span style="font-size: medium">强强和萌萌是一对好朋友。有一天他们在外面闲逛，突然看到前方有一棵紫荆树。这已经是紫荆花飞舞的季节了，无数的花瓣以肉眼可见的速度从紫荆树上长了出来。仔细看看的话，这个大树实际上是一个带权树。每个时刻它会长出一个新的叶子节点。每个节点上有一个可爱的小精灵，新长出的节点上也会同时出现一个新的小精灵。小精灵是很萌但是也很脆弱的生物，每个小精灵 i 都有一个感受能力值Ri ，小精灵 i, j 成为朋友当且仅当在树上 i 和 j 的距离 dist(i,j) ≤ Ri + R! ，其中 dist(i, j)表示在这个树上从 i 到 j 的唯一路径上所有边的边权和。强强和萌萌很好奇每次新长出一个叶子节点之后，这个树上总共有几对朋友。  <br/>
我们假定这个树一开始为空，节点按照加入的顺序从 1开始编号。由于强强非常好奇， 你必须在他每次出现新节点后马上给出总共的朋友对数，不能拖延哦。  </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><br/>
共有 n + 2 行。 <br/>
第一行包含一个正整数，表示测试点编号。 <br/>
第二行包含一个正整数 n ，表示总共要加入的节点数。 <br/>
我们令加入节点前的总共朋友对数是 last_ans，在一开始时它的值为0。 <br/>
接下来 n 行中第 i 行有三个数 ai, bi, ri，表示节点  i  的父节点的编号为 ai xor (last_ans mod 10^9)   (其中xor 表示异或，mod  表示取余，数据保证这样操作后得到的结果介于 1到i  –  1之间)，与父节点之间的边权为 ci，节点 i 上小精灵的感受能力值为r!。 <br/>
注意 a1 = c1 = 0，表示 1 号点是根节点，对于 i &gt; 1，父节点的编号至少为1。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">包含 n 行，每行输出1 个整数， 表示加入第 i 个点之后，树上有几对朋友。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">0 <br/>
5 <br/>
0 0 6 <br/>
1 2 4 <br/>
0 9 4 <br/>
0 5 5 <br/>
0 2 4 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
<br/>
0 <br/>
1 <br/>
2 <br/>
4 <br/>
7 <br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">1&lt;=Ci&lt;=10000<br/><br/>
Ai&lt;=2*10^9<br/><br/>
Ri&lt;=10^9<br/><br/>
N&lt;=100000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

