
# Description

<div class="content"><p><span style="font-size: medium">　　成都的驾驶考试在一个有n条平行的自南向北的单向的道路的场地中进行。每条道路长度为m米，并且都在同一<br/>
条水平线上开始和结束。街道从西向东分别编号为1到n。同样有p条单向的自西向东或自东向西的街道垂直于上面<br/>
描述的街道，每一条这样的街道链接了两个相邻的自南向北的道路。当然自西向东和自东向西的道路可以重叠，那<br/>
就是一个双向的街道了。<br/>
</span></p>
<p><span style="font-size: medium"> <img border="0" alt="" src="/source/bzoj/1107/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExMDdfMS5qcGc=.jpg"/> </span></p>
<p><span style="font-size: medium">　　考生选择一个自南向北的道路作为他考试的起始点和另外一个自南向北的道路作为他考试的终止点。他们的考<br/>
试项目是将车从开始的道路驾驶到作为终止点的道路。考生们总是选择一个可以到达所有其他街道的起始道路作为<br/>
开始点。现在，考生们总是感到十分无趣因为他们只有很少的起始道路可以选择，所以教练们决定改造先有的考试<br/>
场所，由于经费的限制，他们决定添加至多K条东西向的道路，使得能够选择的起始道路尽量地多。<br/>
</span></p></div>

# Input

<div class="content"><p>　　输入第一行包含四个整数n,m,p和k(2&lt;=n&lt;=100000， 1&lt;=m,k&lt;=100000， 0&lt;=p&lt;=100000)。分别表示南北向的道<br/>
路数，南北向道路的长度，东西向的道路数和最多能够添加的道路数。接下来p行，每行包含三个整数ni,mi和di(1<br/>
 &lt; = ni &lt; n，0 &lt; = mi &lt; m，di = 0 or 1)，表示一条自西向东（di = 0）或者自东向西（di = 1）的道路。这<br/>
个道路连接了南北向的道路ni和ni+1，在第mi米的地方进行了连接。</p></div>

# Output

<div class="content"><p>　　输出中仅包含一个整数，最大的能够作为起点的道路数（不包括原来就能作为起点的道路数）。注意添加的道<br/>
路不能与南北向的道路相交，并且到起始水平线的距离为整数。添加的道路可以重叠，表示双向的道路。</p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3 5 2<br/>
2 0 0<br/>
2 2 1<br/>
3 3 1<br/>
1 1 1<br/>
3 3 0<br/>
<img border="0" src="/source/bzoj/1107/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzExMDdfMi5qcGc=.jpg"/><br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

