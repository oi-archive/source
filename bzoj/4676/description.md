
# Description

<div class="content"><div>一个n*m的棋盘，左上角为(1,1),右下角为(n,m)。相邻的2点之间有连边</div>
<div>（如下图中实线）特殊地，(1,i)与(n,i)也连有一条边（如下图中虚线）,i=1..m。</div>
<div>如下图，就是一个n=3,m=4的棋盘。</div>
<div><img src="/source/bzoj/4676/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC8xLnBuZw==.png" width="606" height="445" alt=""/></div>
<div>每个点(i,j)给定2个值a[i][j],b[i][j]。每条边e给定1个值c[e]。</div>
<div>你的任务是给每一个点一个非负的d值，最小化(S1+S2)。</div>
<div><img src="/source/bzoj/4676/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwOC8yLnBuZw==.png" width="573" height="227" alt=""/></div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>第一行2个整数n,m。</div>
<div>接着n行，每行m个数，其中第i行第j个数表示a[i][j]。</div>
<div>接着n行，每行m个数，其中第i行第j个数表示b[i][j]。</div>
<div>接着n行，每行m-1个数，其中第i行第j个数表示(i,j)与(i,j+1)的边的c值。</div>
<div>接着n-1行，每行m个数，其中第i行第j个数表示(i,j)与(i+1,j)的边的c值。</div>
<div>最后一行m个数，其中第i个数表示(1,i)与(n,i)的边的c值。</div>
<div>2&lt;=n&lt;=5， 1&lt;=m&lt;=10000</div>
<div>a,b,c 的值均为不大于 10^6 的正整数</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>一个整数，表示S1+S2的最小值</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
3 6<br/>
7 3<br/>
9 9<br/>
1 8<br/>
9 5<br/>
3 9<br/>
4 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">49</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

