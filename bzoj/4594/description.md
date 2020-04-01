
# Description

<div class="content"><p> 曾经发明了激光发生器的发明家SHTSC又公开了他的新发明：零件组装机--一种可以生产并组装零件的神秘装置。</p>
<div>一个零件是一张顶点由0 到n-1标号的无向图，零件组装机由以下两条功能。</div>
<div>（1）生产一个仅有一个顶点标号为0而没有边的零件。</div>
<div>（2）组合两个已有的零件G1，G2，且G2的顶点数m&gt;=G1的顶点数n，得到新的零件G。G的顶点集合是G1、G2顶点集合的并</div>
<div>集，并且G2的顶点i(0&lt;=i&lt;m)被重新标号为n+i。G的边集是G1、G2边集的并集再对所有标号为a(a&gt;=n)的顶点添加一</div>
<div>条连接(a,a mod n)的无向边。</div>
<div><img src="/source/bzoj/4594/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNS_ml6DmoIfpopgucG5n.png" width="447" height="356" alt=""/></div>
<div>现在SHTSC正在思考，对于一个给定的零件，能否由零件组装机生产组装得到。注意：零件是带标号的，这意味着</div>
<div>两个零件即使仅有标号不同也被视为不同的零件。为了帮助你理解问题，SHTSC特地给了你顶点数&lt;=5的零件的图例。</div>
<div><img src="/source/bzoj/4594/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNS_ml6DmoIfpopgyLnBuZw==.png" width="656" height="563" alt=""/></div>
<div></div></div>

# Input

<div class="content"><p>第一行一个整数t，表示有t组数据。</p>
<div>每组数据的第一行两个整数n，m。表示某个带标号的无向图有n个顶点0到n-1标号，m是边的数量。</div>
<div>接下来m行，每行两个整数u，v表示一条从u到v的无向边。</div>
<div>t&lt;=10，n,m&lt;=100000，0&lt;=u, v&lt;n</div>
<div></div></div>

# Output

<div class="content"><p>对于每组数据，输出一行。如果这个无向图可以被零件制造机制造输出&#34;YES&#34;否则输出&#34;NO&#34;。</p>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">2<br/>
1 0<br/>
2 0</span></div>

# Sample Output

<div class="content"><span class="sampledata">YES<br/>
NO<br/>
//样例1：n=1的情况和一个不能被产生的零件</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By 佚名上传">By 佚名上传</a></p></div>

