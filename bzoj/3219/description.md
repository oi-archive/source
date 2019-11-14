
# Description

<div class="content"><div align="left"><span style="font-size: medium">Tar国正在准备每年一次的巡游活动。国王将会在一个城市S里召集人群，沿着城市间的道路进行游览，最终在一个城市T里发表他每年一次的著名演讲。</span></div>
<div align="left"><span style="font-size: medium">Tar国有N个城市，由于国家的特殊要求，每两个城市之间存在一条唯一的简单通路。</span></div>
<div align="left"><span style="font-size: medium">国王希望借着这个机会视察Tar国的城市建设，因此他提出S到T的距离不能少于L条道路。</span></div>
<div align="left"><span style="font-size: medium">同时，国王的私人医生检查了他的身体情况后，断定国王的身体不适合做长途旅行，因此他要求S到T的距离不能多于R条道路。</span></div>
<div align="left"><span style="font-size: medium">另外，政府希望跟随国王的人民沿途不仅能看到城市风景，还能看到城市外的美丽乡村。因此每条道路定义了一个魅力值Ci，一条路径的魅力值定义为这条路径的<b>中位数</b>。更详细的说法是这样的：</span></div>
<div align="left"><span style="font-size: medium">将路径上所有边的魅力值排序，得到序列{Ai}。假设i=2k+c(0&lt;=c&lt;=1)，中位数就是A(k+1)。</span></div>
<div align="left"><span style="font-size: medium">你的任务就是求出魅力值最大的路径，并输出这个魅力值。</span></div></div>

# Input

<div class="content"><div align="left"><span style="font-size: medium">第一行是三个整数N,L,R，表示Tar国的城市个数、路径的最小和最大长度。</span></div>
<div align="left"><span style="font-size: medium">接下来N-1行，每行3个整数Ai,Bi,Ci，表示有一条连接Ai和Bi且魅力值Ci的道路。</span></div></div>

# Output

<div class="content"><div align="left"> </div>
<div align="left"><span style="font-size: medium">仅一行，表示最大的魅力值。如果不存在这样的路径，输出-1。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 1 4<br/>
1 2 1<br/>
1 3 4<br/>
3 4 7<br/>
3 5 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">7</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据：N&lt;=100000，1&lt;=L&lt;=R&lt;=N-1,1&lt;=Ci&lt;=1000000000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

