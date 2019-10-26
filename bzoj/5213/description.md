
# Description

<div class="content"><div>九条可怜是一个贪玩的女孩子。</div>
<div></div>
<div>暑假快要到了，可怜打算在她家的私人海滩旁边建一座城堡，这样就可以在放暑假的时候邀请她的朋友们来玩了。</div>
<div>同时，可怜打算在城堡的地下修建一座迷宫，因为探险总是一件充满乐趣的事情。经过简单的设计，可怜打算修建</div>
<div>一座这样的迷宫：</div>
<div>1:迷宫可以被抽象成n个点，nm条边的有向图。1号点是唯一的入口也是唯一的出口。</div>
<div>2:每一个点恰好有m条出边，且这些出边被依次标号为[0,m)的正整数。</div>
<div>3:迷宫允许自环和重边。</div>
<div>同时，一座优秀的迷宫应该有一定的解谜因素。因此可怜希望每一条从1号点出发并回到1号点的回路都有着一定的</div>
<div>规律。</div>
<div></div>
<div>可怜发现，如果把一条从1出发的路径经过的所有边的编号都记录下来，那么能得到一个（可能有前导0）的m进制</div>
<div>数；同时对于每一个（可能有前导0）的m进制数，都能对应回一条从1出发的路径。</div>
<div></div>
<div>于是可怜选定了一个整数K，她希望这个迷宫满足一条从1出发的路径能回到1当且仅当这条路径对应的数是K的倍数</div>
<div>。</div>
<div>现在可怜已经选定了m和K，但是她发现并不是对所有的n，都存在满足上述所有条件的迷宫设计方案。建造迷宫是</div>
<div>一件费时费力的事情，于是可怜想要找到一个最小的满足条件的n。然而可怜对复杂的计算并不感兴趣，因此她想</div>
<div>让你来帮她计算一下这个数值。</div>
<div></div>
<div></div></div>

# Input

<div class="content"><div>第一行输入一个整数T表示数据组数。</div>
<div>接下来T行每行两个十进制正整数m,K表示可怜选定的整数。</div>
<div>2&lt;=M&lt;=10^18</div>
<div>K&lt;=10^18</div>
<div>t&lt;=3*10^5</div>
<div></div></div>

# Output

<div class="content"><div>对于每组数据，输出一行一个整数表示能够满足所有条件的最小的n。</div>
<div>如果不存在这样的n，输出-1</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">3<br/>
2 3<br/>
2 4<br/>
6 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
3<br/>
5</span></div>

# Hint

<div class="content"><p></p><p> <img src="/source/bzoj/5213/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwMy8xKDIpLmpwZw==.jpg" width="625" height="196" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

