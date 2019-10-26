
# Description

<div class="content"><div>首先，先介绍仙人掌树。仙人掌树是一张无向图，但是每个节点最多只会在一个环里面，而且这张图的环全部都是简单环，即A-&gt;B-&gt;C-&gt;A这种。</div>
<div>比如下图就是一颗仙人掌树。</div>
<div> <img src="/source/bzoj/3899/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwMy9hYmMuUE5H.PNG" width="418" height="269" alt=""/></div>
<div>好的，知道了仙人掌树之后，我们现在要计算一个东西。</div>
<div>我们现在已经知道了一个N个节点的仙人掌树，称作为原图。接下来，我们要用1-N的一个排列A[1]-A[N]去变换这棵树，具体的，如果原图中有一条边i-j，那么变换出来的图中必须有一条A[i]-A[j]的边。同样的，如果变换出来的图中有一条A[i]-A[j]的边，那么原图中必有一条i-j的边。（简单而言就是点重新编号）</div>
<div>小A为了超脱宇宙的束缚，必须要知道，有多少种排列，可以使得变换出来的新图和原图是一模一样的，具体的，原图中如果存在一条i-j的边，新图也存在一条i-j的边，新图中存在一条i-j的边，原图中也存在i-j的边。</div>
<div>方案数目答案mod 1000000003。</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行有两个正整数，N和M，节点个数和边的个数。</div>
<div>接下来M行，每行有2个正整数S，T，表示一条原图的无向边。数据保证没有重边。</div>
</div>
<div>
<div></div>
</div>
<p></p></div>

# Output

<div class="content"><div>
<div>一行一个正整数表示方案书目。</div>
</div>
<div>
<div></div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 5<br/>
1 2<br/>
2 3<br/>
3 4<br/>
4 5<br/>
1 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">10</span></div>

# Hint

<div class="content"><p></p><div>所有的答案包括(i,(i+1) % 5 + 1,(i+2) % 5 + 1,(i+3) % 5 + 1,(i+4) % 5 + 1)和(i,(i+4) % 5 + 1,(i+3) % 5 + 1,(i+2) % 5 + 1,(i+1) % 5 + 1)这两种类型。每种类型的i可以是12345，所以答案是2*5=10。</div><br/>
<div>N&lt;=1000</div><br/>
<div></div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名提供">By 佚名提供</a></p></div>

