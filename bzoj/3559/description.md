
# Description

<div class="content"><div></div>
<div></div>
<p class="MsoNormal"></p>
<p><img width="1553" height="665" src="/source/bzoj/3559/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTUwNS9iYWNrLlBORw==.PNG" alt=""/></p></div>

# Input

<div class="content"><p></p>
<div>
<div> 输入的第一行包含两个正整数n,m，表示输入的无向图有n个顶点，m条无向边。</div>
<div>第二行包含两个正整数Z[1],Z[2],...,Z[n](Z[i]≤10^9)。</div>
<div>下面m行，每行三个正整数u,v,w(1≤u,v≤n,u≠v,w≤10^9)，表示图中存在一条边(u,v)且权值为w。输入的无向图保证没有重边和自环。</div>
<div></div>
</div>
<div></div></div>

# Output

<div class="content"><div>
<div>输出包含k+1行，第一行包含一个正整数k，表示你给出的分割的度。</div>
<div>
<div>下面k行，每行描述一个C。每行一开始包含一个正整数t，表示|Ci|，然后跟着t个不超过n的正整数，表示C中的顶点编号。</div>
<div></div>
</div>
</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">5 6<br/>
3 3 2 2 1<br/>
1 2 3<br/>
1 3 5<br/>
1 4 6<br/>
2 4 10<br/>
2 5 5<br/>
4 5 8</span></div>

# Sample Output

<div class="content"><span class="sampledata">4<br/>
2 1 2<br/>
1 3<br/>
1 4<br/>
1 5</span></div>

# Hint

<div class="content"><p></p><p>对于10%的数据，满足n=2<br/><br/>
对于30%的数据，满足n≤10<br/><br/>
对于60%的数据，满足n≤500,m≤2000<br/><br/>
对于100%的数据，满足n≤100000,m≤500000<br/><br/>
<br/><br/>
<br/><br/>
</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

