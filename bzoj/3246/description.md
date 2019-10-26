
# Description

<div class="content"><p><span style="font-size: medium">Serpent(水蛇)生活的地方有N个水坑，编号为0，...，N - 1，有M条双向小路连接这些水坑。每两个水坑之间至多有一条路径（路径包含一条或多条小路）相互连接，有些水坑之间根本无法互通(即M ≤ N-1 )。Serpent走过每条小路需要一个固定的天数，不同的小路需要的天数可能不同。Serpent的朋友袋鼠希望新修 N - M - 1条小路，让Serpent可以在任何两个水坑间游走。袋鼠可以在任意两个水坑之间修路，Serpent通过每条新路的时间都是L天。袋鼠希望找到一种修路方式使得修路之后Serpent在每两个水坑之间游走的最长时间最短。</span></p>
<p><span style="font-size: medium">举例说明</span></p>
<p><span style="font-size: medium"><img height="433" width="544" alt="" src="/source/bzoj/3246/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNy8xLmpwZw==.jpg"/></span></p>
<p><span style="font-size: medium">上图中有12个水坑8条小路( N = 12, M = 8)。假如L = 2 ,即Serpent通过任何一条新路都需要2天。那么，袋鼠可以修建3条新路： <br/>
水坑1和水坑2之间；<br/>
水坑1和水坑6之间；<br/>
水坑4和水坑10之间。</span></p>
<p><span style="font-size: medium"><img height="402" width="574" alt="" src="/source/bzoj/3246/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNy8xKDEpLmpwZw==.jpg"/></span></p>
<p><span style="font-size: medium">上图显示了修路后的最终状态。从水坑0走到水坑11的时间最长，需要18天。这是 最佳结果，无论袋鼠如何选择修路方式，总会存在一些水坑对，Serpent需要18天 或者更长时间从其中一个走到另一个。<br/>
 </span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">N : 水坑的数目。<br/>
M : 原本存在的小路的数目。<br/>
L : Serpent通过新修的路经的时间。<br/>
A, B 和 T: 三个包含M个元素的数组，分别表示每条小路的两个端点和通过这条小路的时间。例如，第i条小路连接水坑 A[i-1]和水坑B[i-1],通过这条小路的时间是T[i-1]天。<br/>
 <br/>
 </span></p></div>

# Output

<div class="content"><p><br/>
<font size="4">如上所述，表示游走于两个距离最远的水坑之间所需的时间。</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">12 8 2<br/>
0 8 4<br/>
8 2 2<br/>
2 7 4<br/>
5 11 3<br/>
5 1 7<br/>
1 3 1<br/>
1 9 5<br/>
10 6 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">18</span></div>

# Hint

<div class="content"><p></p><p> <span style="font-family: arial, verdana, helvetica, sans-serif;">n &lt;= 500000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

