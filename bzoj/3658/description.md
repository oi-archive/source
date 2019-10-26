
# Description

<div class="content"><p><span style="font-size: medium">平面上有n个点，每个点有k种颜色中的一个。<br/>
你可以选择一条水平的线段获得在其上方或其下方的所有点，如图所示：</span></p>
<p><span style="font-size: medium"><img height="272" width="293" alt="" src="/source/bzoj/3658/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTQwNy9iYigxKS5qcGc=.jpg"/></span></p>
<p></p>
<p></p>
<p><span style="font-size: medium">请求出你最多能够得到多少点，使得获得的点并不包含所有的颜色。<br/>
    </span></p></div>

# Input

<div class="content"><p><font size="4">包含多组测试数据，第一行输入一个数T表示测试数据组数。<br/>
    接下来T组测试数据，对于每组测试数据，第一行输入两个数n，k，分别表示点的个数和颜色数。<br/>
    接下来n行每行描述一个点，前两个数z，y(lxl，lyl≤2^32-1)描述点的位置，最后一个数z(1≤z≤K）描述点的颜色。<br/>
   </font></p></div>

# Output

<div class="content"><p><font size="4"> 对于每组数据输出一行，每行一个数ans，表示答案。</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
10 3<br/>
1 2 3<br/>
2 1 1<br/>
2 4 2<br/>
3 5 3<br/>
4 4 2<br/>
5 1 2<br/>
6 3 1<br/>
6 7 1<br/>
7 2 3 <br/>
9 4 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">N&lt;=100000，K&lt;=100000，T&lt;=3</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

