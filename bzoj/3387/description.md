
# Description

<div class="content"><div style="text-indent: 11.25pt"><span style="font-size: medium">约翰建造了N(1≤N≤50000)个栅栏来与牛同乐．第i个栅栏的z坐标为[Ai.，Bi]（-100000≤Ai&lt;Bi≤10^5），y坐标为i．牛棚的外栏即x轴，原点是牛棚的门．奶牛们开始处于(S，N)，她们需要回到牛棚的门（下图中用“*’表示）．</span></div>
<div style="text-indent: 11.25pt"><span style="font-size: medium"> <img height="247" alt="" width="410" src="/source/bzoj/3387/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS8yMig0KS5qcGc=.jpg"/></span></div>
<div style="text-indent: 11.25pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 11.25pt"><span style="font-size: medium"> </span><span style="font-size: medium">约翰的初衷是为了给奶牛们练习跳跃，但是奶牛们似乎更愿意四蹄着地，慢慢她沿着栅栏</span></div>
<div><span style="font-size: medium">走．当她们走到栅栏的尽头，就会朝着牛棚的个栏方向（即y轴负方向）行走，直到碰上另一条栅栏或是牛棚外栏．这时候她们便要选择继续向左走，还是向右走．奶牛们希望走的路程最短．由于可方向的路程一定，你只需求出z方向走的最短路程，使奶牛回到原点．</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">    第1行：N，S(-100000≤S≤100000)．</span></div>
<div><span style="font-size: medium">    第2到N+1行：每行2个整数Ai，Bi，(-100000≤Ai≤Bi≤100000)．</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">    最小的x方向的步数</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">    4  0<br/>
    -2  1<br/>
    -1  2<br/>
    -3  0<br/>
    -2  1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    4</span></div>

# Hint

<div class="content"><p></p><p><img height="266" alt="" width="735" src="/source/bzoj/3387/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwMS80NCgxKS5qcGc=.jpg"/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

