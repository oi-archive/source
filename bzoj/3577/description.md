
# Description

<div class="content"><p><span style="font-size: medium">现在有一堆手机放在坐标网格里面（坐标从1开始），坐标(i,j)的格子有s_(i,j)个手机。<br/>
玩手机当然需要有信号，不过这里的手机与基站与我们不太一样。基站分为两种：发送站和接收站（以下简称为A站和B站）。每个手机必须同时与一个A站和一个B站通信才能工作。<br/>
每个基站有一个正方形的覆盖范围（平行于网格）。覆盖范围可以用左下角和右上角的坐标表示（范围包括边角）。显然，手机只有在某个基站的范围内才能与这个基站通信。除此之外，每个基站还有最大接入的手机数量限制。<br/>
求最大同时工作的手机数量。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第一行四个整数R,C,a,b，表示坐标网格的规模是R×C，共有a个A站和b个B站。<br/>
接下来是一个R×C的矩阵，第i行第j列的数为s_(i,j)。<br/>
接下来a行，每行5个数w,x1,y1,x2,y2，表示第i个A站最大接入w个手机，覆盖范围为(x1,y1)～(x2,y2)。<br/>
接下来b行，每行5个数w,x1,y1,x2,y2，含义同上。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">一个整数，即最大同时工作的手机数量。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 1 2<br/>
1 1 1<br/>
1 1 1<br/>
1 1 1<br/>
100 1 1 3 3<br/>
4 1 1 2 2<br/>
4 2 2 3 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7<br/>
<br/>
数据规模与约定<br/>
1≤R,C≤60,0≤a,b≤10,000,0≤s,w≤10,000,1≤x1≤x2≤R,1≤y1≤y2≤C。<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Streaming #2 by saffah
">Streaming #2 by saffah<br/>
</a></p></div>

