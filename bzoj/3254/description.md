
# Description

<div class="content"><div style="text-indent: 24pt"><span style="font-size: 12pt">一个n*m的棋盘，左上角为(1,1),右下角为(n,m)。相邻的2点之间有连边（如下图中实线）特殊地，(1,i)与(n,i)也连有一条边（如下图中虚线）,i=1..m。</span></div>
<div style="text-indent: 21pt"><span style="font-size: 12pt">如下图，就是一个n=3,m=4 的棋盘。</span></div>
<p><img height="640" alt="" width="567" src="/source/bzoj/3254/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTMwOC8xLmpwZw==.jpg"/></p></div>

# Input

<div class="content"><div style="text-indent: 24pt"><span style="font-size: 12pt">第一行2个整数n,m。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">接着n行，每行m个数，其中第i行第j个数表示a[i][j]。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">接着n行，每行m个数，其中第i行第j个数表示b[i][j]。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">接着n行，每行m-1个数，其中第i行第j个数表示(i,j)与(i,j+1)的边的c值。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">接着n-1行，每行m个数，其中第i行第j个数表示(i,j)与(i+1,j)的边的c值。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">最后一行m个数，其中第i个数表示(1,i)与(n,i)的边的c值。</span></div></div>

# Output

<div class="content"><div style="text-indent: 21pt"><span style="font-size: 12pt">一个整数，表示S1+S2的最小值</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">2 2<br/>
3 6<br/>
7 3<br/>
9 9<br/>
1 8<br/>
9<br/>
5<br/>
3 9<br/>
4 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">49<br/>
 </span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">对于100%的数据 2&lt;=n&lt;=5 1&lt;=m&lt;=10000<br/><br/>
a,b,c的值均为不大于10^6的正整数。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

