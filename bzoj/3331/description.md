
# Description

<div class="content"><div><span style="font-size: medium">如今,路由器和交换机构建起了互联网的骨架。处在互联网的骨干位置的</span></div>
<div><span style="font-size: medium">核心路由器典型的要处理100Gbit/s的网络流量。他们每天都生活在巨大的压力</span></div>
<div><span style="font-size: medium">之下。</span></div>
<div><span style="font-size: medium">小强建立了一个模型。这世界上有N个网络设备,他们之间有M个双向的</span></div>
<div><span style="font-size: medium">链接。这个世界是连通的。在一段时间里,有Q个数据包要从一个网络设备发</span></div>
<div><span style="font-size: medium">送到另一个网络设备。</span></div>
<div><span style="font-size: medium">一个网络设备承受的压力有多大呢?很显然,这取决于Q个数据包各自走</span></div>
<div><span style="font-size: medium">的路径。不过,某些数据包无论走什么路径都不可避免的要通过某些网络设</span></div>
<div><span style="font-size: medium">备。</span></div>
<div><span style="font-size: medium">你要计算:对每个网络设备,必须通过(包括起点、终点)他的数据包有</span></div>
<div><span style="font-size: medium">多少个?</span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行包含3个由空格隔开的正整数N,M,Q。</span></div>
<div><span style="font-size: medium">接下来M行,每行两个整数u,v,表示第u个网络设备(从1开始编号)和</span></div>
<div><span style="font-size: medium">第v个网络设备之间有一个链接。u不会等于v。两个网络设备之间可能有多个</span></div>
<div><span style="font-size: medium">链接。</span></div>
<div><span style="font-size: medium">接下来Q行,每行两个整数p,q,表示第p个网络设备向第q个网络设备发</span></div>
<div><span style="font-size: medium">送了一个数据包。p不会等于q。</span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">输出N行,每行1个整数,表示必须通过某个网络设备的数据包的数量。</span></div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4 2<br/>
1 2<br/>
1 3<br/>
2 3<br/>
1 4<br/>
4 2<br/>
4 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
1<br/>
1<br/>
2<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">【样例解释】<br/><br/>
设备1、2、3之间两两有链接,4只和1有链接。4想向2和3各发送一个数据<br/><br/>
包。显然,这两个数据包必须要经过它的起点、终点和1。<br/><br/>
【数据规模和约定】<br/><br/>
对于40%的数据,N,M,Q≤2000<br/><br/>
对于60%的数据,N,M,Q≤40000<br/><br/>
对于100%的数据,N≤100000,M,Q≤200000</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

