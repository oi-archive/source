
# Description

<div class="content"><p>你被雇佣升级一个旧果汁加工厂的橙汁运输系统。系统有管道和节点构成。每条管道都是双向的，且每条管道的流量都是1升每秒。管道可能连接节点，每个节点最多可以连接3条管道。节点的流量是无限的。节点用整数1到n来表示。在升级系统之前，你需要对现有系统进行分析。对于两个不同节点s和t，s-t的流量被定义为：当s为源点，t为汇点，从s能流向t的最大流量。以下面的第一组样例数据为例，1-6的流量为3，1-2的流量为2。计算每一对满足a&lt;b的节点a-b的流量的和。</p></div>

# Input

<div class="content"><p>第一行包括2个整数n和m(2&lt;=n&lt;=3000,0&lt;=m&lt;=4500)——节点数和管道数。<br/>
接下来m行，每行包括两个相异整数a,b(1&lt;=a,b&lt;=n)，表示一条管道连接节点a,b。<br/>
每个节点最多连接3条管道，每对节点最多被一条管道连接。</p></div>

# Output

<div class="content"><p>输出一个整数——每对满足a&lt;b的节点a-b的流量之和。</p></div>

# Sample Input

<div class="content"><span class="sampledata">6 8<br/>
1 3<br/>
2 3<br/>
4 1<br/>
5 6<br/>
2 6<br/>
5 1<br/>
6 4<br/>
5 3    </span></div>

# Sample Output

<div class="content"><span class="sampledata">36</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

