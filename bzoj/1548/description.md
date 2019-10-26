
# Description

<div class="content"><p><img border="0" alt="" src="/source/bzoj/1548/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE1NDguanBn.jpg"/></p></div>

# Input

<div class="content"><p>第一行一个数t(t&lt;=200)，表示测试数据的组数。每一组第一行一个数n(n&lt;=200)，表示棋盘的大小。接下来n行，每行n个数，第i行第j列一个数a[i,j]表示初始棋盘中的每一个数。再接下来n行，每行n个数，第i行第j列一个数b[i,j]表示目标棋盘中的每一个数。其中a[i,j],b[i,j]&lt;=n*n。</p></div>

# Output

<div class="content"><p>对于每组数据，你都要输出一个最小的变换次数，若初始状态不能变换到目标状态则输出”no”。</p></div>

# Sample Input

<div class="content"><span class="sampledata">10<br/>
3<br/>
5 5 6 <br/>
3 2 4 <br/>
7 2 1 <br/>
2 4 2 <br/>
5 1 6 <br/>
5 7 3 <br/>
3<br/>
3 3 5 <br/>
6 2 1 <br/>
1 6 9 <br/>
3 1 3 <br/>
5 6 1 <br/>
2 6 9 <br/>
3<br/>
7 8 3 <br/>
8 5 5 <br/>
3 4 1 <br/>
1 7 3 <br/>
8 8 4 <br/>
5 5 3 <br/>
3<br/>
4 2 6 <br/>
8 1 4 <br/>
8 1 3 <br/>
2 3 4 <br/>
4 6 8 <br/>
1 1 8 <br/>
3<br/>
2 7 1 <br/>
3 2 5 <br/>
8 8 9 <br/>
5 8 8 <br/>
1 9 2 <br/>
2 7 3 <br/>
3<br/>
7 8 3 <br/>
3 6 2 <br/>
2 1 6 <br/>
2 6 8 <br/>
1 2 6 <br/>
7 3 3 <br/>
3<br/>
2 8 3 <br/>
7 2 8 <br/>
6 5 4 <br/>
8 7 6 <br/>
5 2 4 <br/>
2 3 8 <br/>
3<br/>
1 6 8 <br/>
9 8 1 <br/>
3 3 5 <br/>
8 1 9 <br/>
8 6 1 <br/>
3 3 5 <br/>
3<br/>
7 9 4 <br/>
9 7 1 <br/>
2 2 4 <br/>
2 7 4 <br/>
1 9 4 <br/>
7 9 2 <br/>
3<br/>
6 2 2 <br/>
8 6 1 <br/>
7 3 5 <br/>
2 6 6 <br/>
7 2 3 <br/>
1 8 5 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
2<br/>
3<br/>
2<br/>
3<br/>
2<br/>
3<br/>
2<br/>
3<br/>
3<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据范围：测试点 t n 时限 1 t=10 n=3 1s 2 t=10 n&lt;=10 1s 3 t=50 n&lt;=10 1s 4-5 t=200 n&lt;=100 2s 6-7 t=200 n&lt;=200 7s 8-10 t=200 n=200 15s</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=HNOI2009集训Day4">HNOI2009集训Day4</a></p></div>

