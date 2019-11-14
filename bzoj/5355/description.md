
# Description

<div class="content"><div>
<div>给出一棵n 个节点的树，标号为1~n，每个点的父亲标号一定小于他的标号，当然1</div>
<div>号节点就是这棵树的根</div>
<div>现在你需要执行m 次操作，操作有6 种，如下：</div>
<div> </div>
<div>注：①询问中[l,r]范围不一定全部有节点存在（详见样例）</div>
<div>②l,r∈Z 且l,r∈[0,n]</div>
<div>③val∈Z 且val∈[1,2*10^5]</div>
</div>
<div><img src="/source/bzoj/5355/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTgwNS8xMTExLnBuZw==.png" width="761" height="374" alt=""/></div>
<div></div>
<p></p>
<p></p></div>

# Input

<div class="content"><div>第1 行，一个整数T，为测试点编号</div>
<div>第2 行，一个正整数n</div>
<div>接下来的n-1 行，每行一个正整数fai 为i 号点在树上的父亲</div>
<div>第n+2 行，一个正整数m</div>
<div>接下来m 行，每行表示一个操作，格式如题中表格所示</div>
<div>N,M&lt;=10^5</div>
<div></div></div>

# Output

<div class="content"><div>对于每个1、4 操作输出一行，为该询问的答案</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">0<br/>
5<br/>
1<br/>
1<br/>
2<br/>
2<br/>
6<br/>
2 1 0 1 1<br/>
1 1 0 0<br/>
3 2 0 2 1<br/>
5 5 1<br/>
6 3 2<br/>
4 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1<br/>
6</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

