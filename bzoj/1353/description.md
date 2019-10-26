
# Description

<div class="content">给出一个平行四边形的长与高.
给出入口与出口,对于四边形的每条边都有一种Color,非黑即白.
你要找出一条路径,走过的边黑白交替,且长度最短</div>

# Input

<div class="content">第一行给出平行四边形的长与高.且值在[1,500]
第二行给出入口,出口坐标.
下面的字符矩阵代表这个平行四边形每条边的Color</div>

# Output

<div class="content">输出路径的最少长度</div>

# Sample Input

<div class="content"><span class="sampledata">inupt 1<br/>
2 1<br/>
0 0 2 1<br/>
bb<br/>
nwwnw<br/>
bn<br/>
<br/>
input 2<br/>
5 4<br/>
0 2 5 2<br/>
nnbnn<br/>
nnnwwbwnnnn<br/>
nbbbn<br/>
nnwbwwbwwnn<br/>
bwwww<br/>
nnbwbbwwbnn<br/>
nwwwn<br/>
nnnnbwbbnnn<br/>
nnwnn</span></div>

# Sample Output

<div class="content"><span class="sampledata">output 1<br/>
6<br/>
<br/>
output 2<br/>
22<br/>
</span></div>

# Hint

<div class="content"><p>对于第一个数据:<br/>
(0, 0) -&gt; (1, 0) -&gt; (0, 1) -&gt; (1, 1) -&gt; (1, 0) -&gt;(2, 0) -&gt; (2, 1)<br/>
<br/>
<img border="0" src="/source/bzoj/1353/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEzNTMuanBn.jpg"/><br/>
<br/>
对于第二个数据:<br/>
(0, 2) -&gt; (1, 2) -&gt; (1, 1) -&gt; (2, 1) -&gt; (2, 0) -&gt;<br/>
(3, 0) -&gt; (3, 1) -&gt; (3, 2) -&gt; (4, 1) -&gt; (3, 1) -&gt;<br/>
(3, 0) -&gt; (2, 0) -&gt; (2, 1) -&gt; (1, 1) -&gt; (1, 2) -&gt;<br/>
(1, 3) -&gt; (2, 3) -&gt; (2, 4) -&gt; (3, 4) -&gt; (3, 3) -&gt;<br/>
(4, 3) -&gt; (4, 2) -&gt; (5, 2)</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

