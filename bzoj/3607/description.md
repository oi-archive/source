
# Description

<div class="content"><p><span style="font-size: medium">    一个简单的网络数据交换系统可以被描述成一棵带权无根树。每个叶子为用户，而非叶子节点则为服务器。连接服务器（或用户）与服务器的数据线则看做一条树边，边权可以看做这条数据线的长度。<br/>
　　两两用户之间的一次数据交换请求都可以看做这个无根树上的一条从一个叶子到另一个叶子的路径。并且，这次数据交换请求将会激活路径上的所有服务器。对于一个服务器，如果在某一时刻有至少一条数据通过，则这个服务器是激活的，反之则是失活的。同样地，这条请求也会激活路径上的所有数据线。<br/>
　　现在，你作为一个交换系统的管理员，要监控整个系统的运作状态。由于系统还未开发完全，你只能知道在每个时刻，有多少条数据交换的请求，以及登记某个被激活的服务器的编号（毕竟你一秒钟也干不了太多事）。<br/>
　　你连续监控了一段时间。现在，你要开始整理自己的监控记录了。为了检测系统的负荷是否过重，对于每条监控记录，你要求出最坏情况下，被激活的数据线长度的和的最大值。<br/>
　　为什么是数据线长度而不是服务器个数呢？因为出题人不喜欢单位 1。</span></p>
<p></p></div>

# Input

<div class="content"><p><span style="font-size: medium">　　第一行二个整数 n, m，分别描述树的大小，以及监控记录的数量。<br/>
　　接下来 n - 1 行，每行 3 个整数 a, b, v，描述一条连接 a, b 的权值为 v 的边。<br/>
　　接下来 m 行，每行 2 个整数 d, s, 描述一个监控记录。d 表示登记的服务器的编号，s表示请求的数量。</span></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">　　对于每个监控记录，输出一行一个整数，描述答案。</span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">    6 3 <br/>
    1 2 2<br/>
    2 3 2<br/>
    3 4 2<br/>
    4 6 1 <br/>
    3 5 10<br/>
    3 1<br/>
    4 1<br/>
    2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">    14<br/>
    13<br/>
    17<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">    对于记录 (3, 1) , 一种最坏情况为 { (1-&gt;2-&gt;3-&gt;5) }<br/><br/>
　　对于记录 (4, 1) , 一种最坏情况为 { (6-&gt;4-&gt;3-&gt;5) }<br/><br/>
　　对于记录 (2, 2) , 一种最坏情况为 { (6-&gt;4-&gt;3-&gt;5), (1-&gt;2-&gt;3-&gt;4-&gt;6) }</span></p><br/>
<p><span style="font-size: medium">【Range】<br/><br/>
　  n, m ≤ 100000，∑v ≤ maxlongint，1 ≤ d ≤ n 且保证 d 不为叶子节点。</span></p><br/>
<p><span style="font-size: medium">    输入均为非负整数。<br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2014年国家集训队十五人互测 鸣谢sumix173上传
">2014年国家集训队十五人互测 鸣谢sumix173上传<br/>
</a></p></div>

