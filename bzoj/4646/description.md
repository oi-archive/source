
# Description

<div class="content"><div>有一个n*m的网格，除了最左边一列和最右边一列，每个格子上有一些</div>
<div>管道，需要通过旋转一些格子使得最右边一列上的一些格子能够通过管道与至</div>
<div>少一个最左边一列的格子连通。每个格子上的管道都是由一个中间管道扩展到</div>
<div>四个方向中的若干个，也就是说，这个格子的四个方向上如果有管道，那么这</div>
<div>些方向是联通的。例如上方、左方和右方有管道，那么这三个方向的格子如果</div>
<div>有朝向这个格子的管道，就可以通过这个格子上的管道连通。</div>
<div>比如这样：</div>
<div><img src="/source/bzoj/4646/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNy8xMS5wbmc=.png" width="293" height="138" alt=""/></div>
<div>问最右边一列的格子最多有几个同时与最左边一列的格子连通。</div>
<div></div></div>

# Input

<div class="content"><div>多组数据。</div>
<div>对于每组数据，第一行有两个整数n和m，为网格图的行数和列数</div>
<div>下接N行，每行m-2个整数Xi,j，表示网格图第i行第j+l列的管道，如</div>
<div>果xi,j and l=1，那么向上有管道，如果Xi,j and 2=2，那么向右有管道，如</div>
<div>果xi,jand 4=4，那么向下有管道，如果Xi,j and 8=8，那么向左有管道。</div>
<div>l&lt;=n&lt;=9，3&lt;=m&lt;=20，数据组数在5以内</div></div>

# Output

<div class="content"><div>若干行，每行一个数，表示一组数据的答案。</div></div>

# Sample Input

<div class="content"><span class="sampledata">1 3<br/>
5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
//将中间的格子旋转成向左和向右连通即可。<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

