
# Description

<div class="content"><p><span style="font-size: medium">N个点，M条边的有向图，求点1到点N的最短路（保证存在）。<br/>
1&lt;=N&lt;=1000000，1&lt;=M&lt;=10000000</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium"><br/>
第一行两个整数N、M，表示点数和边数。<br/>
第二行六个整数T、rxa、rxc、rya、ryc、rp。</span></p>
<p><span style="font-size: medium">前T条边采用如下方式生成：<br/>
1.初始化x=y=z=0。<br/>
2.重复以下过程T次：<br/>
x=(x*rxa+rxc)%rp;<br/>
y=(y*rya+ryc)%rp;<br/>
a=min(x%n+1,y%n+1);<br/>
b=max(y%n+1,y%n+1);<br/>
则有一条从a到b的，长度为1e8-100*a的有向边。</span></p>
<p><span style="font-size: medium">后M-T条边采用读入方式：<br/>
接下来M-T行每行三个整数x,y,z，表示一条从x到y长度为z的有向边。</span></p>
<p><span style="font-size: medium">1&lt;=x,y&lt;=N，0&lt;z,rxa,rxc,rya,ryc,rp&lt;2^31</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium"><br/>
一个整数，表示1~N的最短路。</span></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
0 1 2 3 5 7<br/>
1 2 1<br/>
1 3 3<br/>
2 3 1<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p>【注释】<br/><br/>
请采用高效的堆来优化Dijkstra算法。</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=WC2013营员交流-lydrainbowcat

">WC2013营员交流-lydrainbowcat<br/>
<br/>
</a></p></div>

