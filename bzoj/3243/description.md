
# Description

<div class="content"><p><span style="font-size: medium">两个d 维向量A=[a1,a2,...,ad]与B=[b1,b2,...,bd]的内积为其相对应维度的权值的乘积和，即：</span></p>
<p><span style="font-size: medium"><img height="61" alt="" width="308" src="source/bzoj/3243/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwNy8yMigxKS5qcGc=.jpg"/></span></p>
<p><span style="font-size: medium">现有 n 个d 维向量x1,...,xn ，小喵喵想知道是否存在两个向量的内积为k的倍数。请帮助她解决这个问题</span></p></div>

# Input

<div class="content"><div>第一行包含3个正整数n,d,k，分别表示向量的个数，维数以及待检测的倍数。接下来n行每行有d个非负整数，其中</div>
<div>第i行的第j个整数表示向量xi的第j维权值xi,j。</div>
<div>N&lt;=100000,D&lt;=30,K&lt;=3,Xi,j&lt;10</div></div>

# Output

<div class="content"><div>包含两个整数，用空格隔开。如果存在两个向量xp,xq的内积为k的整数倍，则输出两个向量的编号p与q（要求p&lt;q</div>
<div>）。如果存在多组这样的向量组合，输出其中任意一组即可。若不存在这样的向量组合，则输出两个-1。</div></div>

# Sample Input

<div class="content"><span class="sampledata">2 20 2<br/>
0 0 1 1 1 1 1 0 1 1 1 0 1 0 0 0 1 1 1 1<br/>
1 0 1 0 1 0 1 1 1 1 0 1 1 1 0 1 1 0 1 0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2<br/>
</span></div>

# Hint

<div class="content"><p></p><p>新增数据一组,但未重测By TA1111,2016.5.17</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

