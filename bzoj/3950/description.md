
# Description

<div class="content"><div>
<div>一个简单的网络数据交换系统可以被描述成一棵带权无根树。每个叶子为用户，而非叶子节点则为服务器。连接服</div>
<div>务器（或用户）与服务器的数据线则看做一条树边，边权可以看做这条数据线的长度。两两用户之间的一次数据交</div>
<div>换请求都可以看做这个无根树上的一条从一个叶子到另一个叶子的路径。并且，这次数据交换请求将会激活路径上</div>
<div>的所有服务器。对于一个服务器，如果在某一时刻有至少一条数据通过，则这个服务器是激活的，反之则是失活的</div>
<div>。同样地，这条请求也会激活路径上的所有数据线。比方说，下图描述了一个有 3 个用户， 2 个服务器的系统。</div>
<div>若存在一条 (4, 5) 请求，则服务器 3 被激活，而服务器 2 未激活；数据线 (4, 3), (3, 5) 被激活，(1, 2), </div>
<div>(2, 3) 未被激活。</div>
</div>
<div></div>
<div><img src="source/bzoj/3950/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNC9jY2MucG5n.png" width="179" height="411" alt=""/></div>
<div>
<div>现在，你作为一个交换系统的管理员，要监控整个系统的运作状态。由于系统还未开发完全，你只能知道在每个时</div>
<div>刻，有多少条数据交换的请求，以及登记某个被激活的服务器的编号（毕竟你一秒钟也干不了太多事）。你连续监</div>
<div>控了一段时间。现在，你要开始整理自己的监控记录了。为了检测系统的负荷是否过重，对于每条监控记录，你要</div>
<div>求出最坏情况下，被激活的数据线长度的和的最大值。为什么是数据线长度而不是服务器个数呢？因为出题人不喜</div>
<div>欢单位 1。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行二个整数n,m，分别描述树的大小，以及监控记录的数量。接下来n-1行，每行3个整数a,b,v，描述一条连接</div>
<div>a,b的权值为v的边。接下来m行，每行2个整数d,s,描述一个监控记录。d表示登记的服务器的编号，s表示请求的数</div>
<div>量。</div>
</div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>对于每个监控记录，输出一行一个整数，描述答案。</div>
<div>
<div></div>
</div>
<div>
<p></p>
</div></div>

# Sample Input

<div class="content"><span class="sampledata">6 3<br/>
1 2 2<br/>
2 3 2<br/>
3 4 2<br/>
4 6 1<br/>
3 5 10<br/>
3 1<br/>
4 1<br/>
2 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">14<br/>
13<br/>
17</span></div>

# Hint

<div class="content"><p></p><div>样例说明</div><br/>
<div>对于记录 (3, 1) , 一种最坏情况为 { (1-&gt;2-&gt;3-&gt;5) }</div><br/>
<div>对于记录 (4, 1) , 一种最坏情况为 { (6-&gt;4-&gt;3-&gt;5) }</div><br/>
<div>对于记录 (2, 2) , 一种最坏情况为 { (6-&gt;4-&gt;3-&gt;5), (1-&gt;2-&gt;3-&gt;4) }</div><br/>
<div>数据规模和约定</div><br/>
<div>一共 20 个测试点。</div><br/>
<div>对于 30% 的数据，有 n, m ≤ 100</div><br/>
<div>另有 20% 的数据，保证所有监控记录的 d 相同。</div><br/>
<div>另有 20% 的数据，生成树随机。</div><br/>
<div>对于 100% 的数据，有 n, m ≤ 100000，∑v ≤ maxlongint，1 ≤ d ≤ n 且保证 d 不为叶子节点。</div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014年国家集训队十五人互测">2014年国家集训队十五人互测</a></p></div>

