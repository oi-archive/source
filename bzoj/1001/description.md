
# Description

<div class="content"><div>现在小朋友们最喜欢的&#34;喜羊羊与灰太狼&#34;,话说灰太狼抓羊不到，但抓兔子还是比较在行的，</div>
<div>而且现在的兔子还比较笨，它们只有两个窝，现在你做为狼王，面对下面这样一个网格的地形：</div>
<p><span style="font-size: medium"> <img border="0" alt="" src="/source/bzoj/1001/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEwMDEuanBn.jpg"/> </span></p>
<div>左上角点为(1,1),右下角点为(N,M)(上图中N=4,M=5).有以下三种类型的道路 </div>
<div>1:(x,y)&lt;==&gt;(x+1,y) </div>
<div>2:(x,y)&lt;==&gt;(x,y+1) </div>
<div>3:(x,y)&lt;==&gt;(x+1,y+1) </div>
<div>道路上的权值表示这条路上最多能够通过的兔子数，道路是无向的. 左上角和右下角为兔子的两个窝，</div>
<div>开始时所有的兔子都聚集在左上角(1,1)的窝里，现在它们要跑到右下解(N,M)的窝中去，狼王开始伏击</div>
<div>这些兔子.当然为了保险起见，如果一条道路上最多通过的兔子数为K，狼王需要安排同样数量的K只狼，</div>
<div>才能完全封锁这条道路，你需要帮助狼王安排一个伏击方案，使得在将兔子一网打尽的前提下，参与的</div>
<div>狼的数量要最小。因为狼还要去找喜羊羊麻烦.</div></div>

# Input

<div class="content"><div>第一行为N,M.表示网格的大小，N,M均小于等于1000.</div>
<div>接下来分三部分</div>
<div>第一部分共N行，每行M-1个数，表示横向道路的权值. </div>
<div>第二部分共N-1行，每行M个数，表示纵向道路的权值. </div>
<div>第三部分共N-1行，每行M-1个数，表示斜向道路的权值. </div>
<div>输入文件保证不超过10M</div></div>

# Output

<div class="content"><p><span style="font-size: medium">输出一个整数，表示参与伏击的狼的最小数量. </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 4<br/>
5 6 4<br/>
4 3 1<br/>
7 5 3<br/>
5 6 7 8<br/>
8 7 6 5<br/>
5 5 5<br/>
6 6 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">14</span></div>

# Hint

<div class="content"><p></p><p> 2015.4.16新加数据一组，可能会卡掉从前可以过的程序。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

