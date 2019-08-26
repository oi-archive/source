
# Description

<div class="content"><div>你现在要为智能汽车负责设计一种很高级的集中管理系统。目的是利用全球信息指导早上从郊区赶往市中心的乘客如何在避免交通堵塞的情况下更好地到达城市中心。</div>
<div>不幸的是，乘客们对城市非常了解，而且都相当自私，你不能简单地甩给他们一条比平常走的还要长的路径（否则他们会直接无视你的指导），所以只能说服他们改走另外一条长度相同的路径。</div>
<div>城市的道路网络由路口和连接它们的双向道路组成，通过不同的道路所需时间是不同的。所有乘客都会从各自的路口出发，当然不同的乘客出发的路口可能不同。但是所有乘客都会在同一个地点结束他们的旅程，那就是位于路口1的市中心。如果两个乘客试图在相同的时间，从同一方向，开始沿着相同的道路移动，就会出现堵塞——这是你必须避免种情况的。但是，两名乘客可以在同一时间通过同一个路口，或者在不同时间从同一条道路沿同一方向出发。</div>
<div>请确定最多能有多少人能够在没有堵塞的前提下开车前往市中心。注意，所有乘客刚好在同一时间从他们所在路口出发，而且乘客只会走能够最快到达路口1的路径。</div>
<div><img src="source/bzoj/3955/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC9mZmYuYm1w.bmp" width="290" height="278" alt=""/></div>
<div>在图C.1中，汽车图案标记了每名乘客最开始所在的路口，其中一辆车已经在市中心了。而路口4的车辆，可以走通过路口3的红色的点线，或者通过路口2的蓝色虚线。但是剩下的两辆车不可能在避免堵塞的前提下前往市中心。所以，在避免堵塞的情况下，最多只有3辆车能够抵达位于路口1的市中心。</div>
<p></p></div>

# Input

<div class="content"><div>输入只会包含一组数据。第一行是三个正整数n,m,c，其中n(1≤n≤25000)是路口的个数，m(0≤m≤50000)是连接路口的道路的个数，而c(1≤c≤1000)则是乘客的个数。接下来m行，每行有三个正整数xi,yi,zi来描述一条道路，xi,yi是该道路连接的两个不同的路口，而ti，是开车通过这个道路的时间（两个方向的时间一样）。所有的路口都能够抵达市中心。最后一行的c个数，分别代表了c个乘客出发的路口。</div>
<p></p></div>

# Output

<div class="content"><div>
<div>一个整数，表示在没有堵塞的情况下最多有多少乘客能够抵达市中心。</div>
</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3 2<br/>
1 2 42<br/>
2 3 1<br/>
2 3 1<br/>
2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

