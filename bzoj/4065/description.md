
# Description

<div class="content"><p> 在Byteland有两家领导显卡行业的制作商：Bitotronics和3D-Bytes。他们顶级的显卡十分相像。每一个都包含一些电线连接节点，用来维护电信号传播。产品包括两种节点：插座和处理器。这种有线网络满足以下条件：</p>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>每个插座都恰好和一个处理器相连，不和任何其他插座相连。</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>每个处理器都和至少两个其他的节点相连。</div>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>任意两个在网络中的节点，都只存在唯一的电线路径链接他们。换句话说，这些节点之间的连通图可以被看成是一棵树。</div>
<div>Bitthew喜欢焊接计算机的硬件设备。他拿出了来自两个不同厂家的显卡，两个显卡拥有相同数量的插座，他决定将每个Bitotronics卡上的插座与3D-Bytes卡上的插座用电缆一一相连。他得到的装置如图：</div>
<div> </div>
<div>Bitthew想要从装置中获得出最大的性能。为了实现这个目标，他想要找到一条由电线和电缆组成的路径来维护电信号。这条路径应该访问每个节点恰好一次，且这条路径的起始节点和终止节点应该在同一个节点。请你帮助Bitthew检查一下现在的装置是否能找到这样的路径。</div>
<div><img src="/source/bzoj/4065/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS9LLmpwZw==.jpg" width="244" height="221" alt=""/></div></div>

# Input

<div class="content"><p>第一行一个正整数T，表示有T组数据。</p>
<div>
<div>每组数据第一行三个整数k, n, m，表示每个卡有k个插座，Bitotronics卡有n个处理器，3D-Bytes卡有m个处理器，2 &lt;= k &lt;= 1000, 1 &lt;= n, m &lt;= 1000。卡上的节点按照以下形式命名：</div>
<div><span class="Apple-tab-span" style="white-space: pre;">	</span>Bitotronics卡的插座：AS1, AS2, ..., Ask</div>
<div><span class="Apple-tab-span" style="white-space: pre;">	</span>Bitotronics卡的处理器：AP1, AP2, ..., APn</div>
<div><span class="Apple-tab-span" style="white-space: pre;">	</span>3D-Bytes卡的插座：BS1, BS2, ..., BSk</div>
<div><span class="Apple-tab-span" style="white-space: pre;">	</span>3D-Bytes卡的处理器：BP1, BP2, ..., BPm</div>
<div>接下来n+k-1行描述Bitotronics卡的情况，每行两个节点的名字，表示这两个节点之间有电线相连。接下来一行为空行。</div>
<div>接下来m+k-1行描述3D-Bytes卡的情况，每行两个节点的名字，表示这两个节点之间有电线相连。接下来一行为空行。</div>
<div>接下来k行描述两卡之间的情况，每行两个节点的名字，表示这两个节点之间有电缆相连，保证每个插座在这k行里均只出现一次。</div>
<div>每组数据之间会有一个空行。</div>
</div></div>

# Output

<div class="content"><p>对于每组数据，如果不存在这样的路径，输出一行&#34;NO&#34;，否则先输出一行&#34;YES&#34;，再在其后按照路径上的顺序输出n+m+2k个节点，相邻的节点必须通过电线或电缆直接相连，而且第一个点必须和最后一个点也直接相连，按照任意顺序输出，节点名称和”YES”之间空格隔开。（不含引号）</p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
2 1 11<br/>
AS1 AP1<br/>
AS2 AP1<br/>
BS1 BP1<br/>
<br/>
BS2 BP11<br/>
BP1 BP2<br/>
BP2 BP3<br/>
BP3 BP4<br/>
BP4 BP5<br/>
BP5 BP6<br/>
BP6 BP7<br/>
BP7 BP8<br/>
BP8 BP9<br/>
BP9 BP10<br/>
BP10 BP11<br/>
<br/>
AS1 BS2<br/>
BS1 AS2<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES BP11 BP10 BP9 BP8 BP7 BP6 BP5 BP4 BP3 BP2 BP1 BS1 AS2 AP1 AS1 BS2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=鸣谢Tjz">鸣谢Tjz</a></p></div>

