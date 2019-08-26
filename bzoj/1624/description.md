
# Description

<div class="content"><div><span style="font-size: medium">    农夫约翰正驾驶一条小艇在牛勒比海上航行．</span></div>
<div><span style="font-size: medium">    海上有N(1≤N≤100)个岛屿，用1到N编号．约翰从1号小岛出发，最后到达N号小岛．一</span></div>
<div><span style="font-size: medium">张藏宝图上说，如果他的路程上经过的小岛依次出现了Ai，A2，…，AM(2≤M≤10000)这样的序列（不一定相邻），那他最终就能找到古老的宝藏．  但是，由于牛勒比海有海盗出没．约翰知道任意两个岛屿之间的航线上海盗出没的概率，他用一个危险指数Dij(0≤Dij≤100000)来描述．他希望他的寻宝活动经过的航线危险指数之和最小．那么，在找到宝藏的前提下，这个最小的危险指数是多少呢？</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行输入N和M，之后M行一行一个整数表示A序列，之后输入一个NxN的方阵，表示两两岛屿之间航线的危险指数．数据保证Dij=Dji，Dii=0．</span></div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium">    最小的危险指数和．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
1<br/>
2<br/>
1<br/>
3<br/>
0 5 1<br/>
5 0 2<br/>
1 2 0<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
There are 3 islands and the treasure map requires Farmer John to<br/>
visit a sequence of 4 islands in order: island 1, island 2, island<br/>
1 again, and finally island 3. The danger ratings of the paths are<br/>
given: the paths (1, 2); (2, 3); (3, 1) and the reverse paths have<br/>
danger ratings of 5, 2, and 1, respectively.<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
<br/>
OUTPUT DETAILS:<br/>
<br/>
He can get the treasure with a total danger of 7 by traveling in<br/>
the sequence of islands 1, 3, 2, 3, 1, and 3. The cow map&#39;s requirement<br/>
(1, 2, 1, and 3) is satisfied by this route. We avoid the path<br/>
between islands 1 and 2 because it has a large danger rating.<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

