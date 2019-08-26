
# Description

<div class="content"><p> 路由是指通过计算机网络把信息从源地址传输到目的地址的活动，也是计算机网络设计中的重点和难点。网络中实现路由转发的硬件设备称为路由器。为了使数据包最快的到达目的地，路由器需要选择最优的路径转发数据包。例如在常用的路由算法OSPF(开放式最短路径优先)中，路由器会使用经典的Dijkstra算法计算最短路径，然后尽量沿最短路径转发数据包。现在，若已知一个计算机网络中各路由器间的连接情况，以及各个路由器的最大吞吐量（即每秒能转发的数据包数量），假设所有数据包一定沿最短路径转发，试计算从路由器1到路由器n的网络的最大吞吐量。计算中忽略转发及传输的时间开销，不考虑链路的带宽限制，即认为数据包可以瞬间通过网络。路由器1到路由器n作为起点和终点，自身的吞吐量不用考虑，网络上也不存在将1和n直接相连的链路。</p>
<div></div></div>

# Input

<div class="content"><p>输入文件第一行包含两个空格分开的正整数n和m，分别表示路由器数量和链路的数量。网络中的路由器使用1到n编号。接下来m行，每行包含三个空格分开的正整数a、b和d，表示从路由器a到路由器b存在一条距离为d的双向链路。 接下来n行，每行包含一个正整数c，分别给出每一个路由器的吞吐量。</p>
<div>
<div></div>
</div></div>

# Output

<div class="content"><p>输出一个整数，为题目所求吞吐量。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">7 10<br/>
1 2 2<br/>
1 5 2<br/>
2 4 1<br/>
2 3 3<br/>
3 7 1<br/>
4 5 4<br/>
4 3 1<br/>
4 6 1<br/>
5 6 2<br/>
6 7 1<br/>
1<br/>
100<br/>
20<br/>
50<br/>
20<br/>
60<br/>
1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">70</span></div>

# Hint

<div class="content"><p></p><p> 对于100%的数据，n≤500，m≤100000，d,c≤10^9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

