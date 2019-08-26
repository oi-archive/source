
# Description

<div class="content"><div><span style="font-size: medium">       BIA机构内部使用一个包含N台计算机的网络。每台计算机被标号为1..N，并且1号机是服务器。计算机被一些单向传输线连接着，每条数据线连接两台计算机。服务器可以向任何一台计算机直接或者间接的发送数据包。</span></div>
<div><span style="font-size: medium">       当BIA得到新的信息，数据被放在服务器上，然后通过网络分发到各台计算机。BIA的首脑在考虑如果一台计算机停止工作（例如被黑客攻击）将会发生什么，有可能一些计算机将因此得不到服务器上的数据。我们称这种计算机是critical的。</span></div>
<div><span style="font-size: medium">       如下图，有两台critical计算机1、2。1是服务器，而所有1到3的数据都必须经过2。</span></div>
<div><span style="font-size: medium"> </span></div>
<p><img height="292" alt="" width="346" src="source/bzoj/3541/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNC8yMi5qcGc=.jpg"/></p></div>

# Input

<div class="content"><p><span style="font-size: medium">N , M （N为点数，M为边数） N≤5000 , N-1≤M≤200000<br/>
 接下来M行每行两个数表示每条连接线的出发计算机和接收计算机的编号。<br/>
</span></p></div>

# Output

<div class="content"><p><font size="4">第一行有一个整数K表示critical计算机的数目<br/>
第二行包含K个整数描述了所有critical计算机的编号。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
1 2<br/>
1 4<br/>
2 3<br/>
3 4<br/>
4 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1 2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

