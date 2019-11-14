
# Description

<div class="content"><div>小P最近遇上了大麻烦，他的高等代数挂科了。于是他只好找高代老师求情。善良的高代老师答应不挂他，但是要</div>
<div>求小P帮助他一起解决一个难题。问题是这样的，高代老师近期要组织班上同学一起去漂流，漂流可以看做是在一</div>
<div>张n个点m条边的有向无环图上进行的，点编号从0到n-1，表示景点；边是连接各景点的一定长度的河道。同时，定</div>
<div>义编号为s是起点而t是终点。我们不妨把从s点到t点不论走什么样的路径都需要经过的边称为桥，这些桥由于地势</div>
<div>险要所以是危险的。现在高代老师有两条长度为l的安全绳，他希望用这两条安全绳覆盖尽可能长的桥，使得他们</div>
<div>通过的桥的长度之和尽量短。</div></div>

# Input

<div class="content"><div>本题包含多组数据，第一行是一个数T(T&lt;=5)表示数据组数</div>
<div>对于每组数据，第一行是5个数，n,m,s,t,l。</div>
<div>以下m行，每行包括三个数si,ti,pi,表示从si到ti有一条长度为pi的单向边。</div>
<div>n&lt;=100000,m&lt;=200000,0&lt;=s,t,si,ti&lt;n, l&lt;=10^9,pi&lt;=100</div></div>

# Output

<div class="content"><div>
<div>对于每组数据，输出一行，包括一个整数，为最优情况下通过的桥的长度之和。</div>
<div>如果不存在从s到t的路径，请输出-1</div>
</div>
<div></div></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
8 9 0 7 7<br/>
0 4 1<br/>
0 1 10<br/>
1 2 9<br/>
4 2 2<br/>
2 5 8<br/>
4 3 3<br/>
5 6 6<br/>
5 6 7<br/>
6 7 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

