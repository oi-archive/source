
# Description

<div class="content"><p><font size="3"><br/>
</font></p>
<p><span style="font-size: medium; "><span class="Apple-tab-span" style="white-space: pre; ">	</span>给出1棵N个节点的树，每条边上有一条权值，对于所有不同的点对(u,v u&lt;v)之间的路径按长度进行排序。要求输出前M长的路径长度。</span></p>
<p><font size="3"><br/>
</font></p></div>

# Input

<div class="content"><p></p>
<p><span style="font-size: medium; "><br class="Apple-interchange-newline"/>
第一行有2个整数N,M，接下来N-1行每行有3个整数u,v,w(1&lt;=u,v&lt;=N,0&lt;=w&lt;=32767)代表了顶点u和v之间有一条长度为w的边</span></p>
<p><font size="3"><br/>
</font></p></div>

# Output

<div class="content"><p><span style="font-size: medium; ">输出M行，第i行输出第i长的路径长度</span></p>
<p><font size="3"><br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 3<br/>
<br/>
1 2 0<br/>
<br/>
2 3 4<br/>
<br/>
2 4 5<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">9<br/>
<br/>
5<br/>
<br/>
5<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p> 对于20%的数据，有N&lt;=1000</p><br/>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>对于50%的数据，有N&lt;=10000</div><br/>
<div><span class="Apple-tab-span" style="white-space:pre">	</span>对于100%的数据，有N&lt;=50000，M&lt;=min(N*(N-1)/2,300000)</div><br/>
<div></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=By abs">By abs</a></p></div>

