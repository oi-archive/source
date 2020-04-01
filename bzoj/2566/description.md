
# Description

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　有一棵含</span><span style="color: #200000">N</span><span style="color: #200000">个结点的树，树上每条边</span><span style="color: #200000">(ai,bi)</span><span style="color: #200000">都有一个权值</span><span style="color: #200000">wi</span><span style="color: #200000">。树上每个结点涂有一个初始颜色</span><span style="color: #200000">ci</span><span style="color: #200000">。现在有很多次修改操作，第</span><span style="color: #200000">i</span><span style="color: #200000">次修改会将结点</span><span style="color: #200000">xi</span><span style="color: #200000">的颜色修改成</span><span style="color: #200000">yi</span><span style="color: #200000">。请在所有修改前和每次修改之后输出一个数，表示对应时刻最近的同色结点对的距离。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　其中，距离定义为树上两点的最短路的距离。最短路按边的权值</span><span style="color: #200000">wi</span><span style="color: #200000">计算。</span></span></div></div>

# Input

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　第一行一个数</span><span style="color: #200000">N</span><span style="color: #200000">。第二行</span><span style="color: #200000">N</span><span style="color: #200000">个数依次给出每个结点的初始颜色</span><span style="color: #200000">ci</span><span style="color: #200000">。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　下面</span><span style="color: #200000">N-1</span><span style="color: #200000">行每行三个数</span><span style="color: #200000">ai,bi,wi</span><span style="color: #200000">，表示一条权值为</span><span style="color: #200000">wi</span><span style="color: #200000">的树边</span><span style="color: #200000">(ai,bi)</span><span style="color: #200000">。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　下面一个数</span><span style="color: #200000">M</span><span style="color: #200000">表示修改次数。</span><span style="color: #200000"><br/>
</span><span style="color: #200000">　　下面</span><span style="color: #200000">M</span><span style="color: #200000">行每行两个数</span><span style="color: #200000">xi,yi</span><span style="color: #200000">，表示将结点</span><span style="color: #200000">xi</span><span style="color: #200000">的颜色修改为</span><span style="color: #200000">yi</span><span style="color: #200000">。</span></span></div></div>

# Output

<div class="content"><div style="background: white" align="left"><span style="font-size: medium"><span style="color: #200000">　　输出包含</span><span style="color: #200000">M+1</span><span style="color: #200000">行，第一行表示初始局面的最近同色结点对距离，下面</span><span style="color: #200000">M</span><span style="color: #200000">行依次表示每次修改后的最近同色结点对距离。如果某时刻没有同色点对，则在对应行输出</span><span style="color: #200000">-1</span><span style="color: #200000">。</span></span></div></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
2 2 3 2 3<br/>
3 5 9<br/>
1 3 1<br/>
2 1 2<br/>
4 1 8<br/>
4<br/>
2 3<br/>
2 1<br/>
1 1<br/>
2 2<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
8<br/>
2<br/>
9<br/>
</span></div>

# Hint

<div class="content"><p></p><p>样例说明<br/><br/>
　　每行输出对应的解释为：<br/><br/>
　　2 -&gt; 最近的是1和2，颜色均为2，距离为2<br/><br/>
　　3 -&gt; 最近的是2和3，颜色均为3，距离为3<br/><br/>
　　8 -&gt; 最近的是1和4，颜色均为2，距离为8<br/><br/>
　　2 -&gt; 最近的是1和2，颜色均为1，距离为2<br/><br/>
　　9 -&gt; 最近的是3和5，颜色均为3，距离为9<br/><br/>
数据规模和约定<br/><br/>
　　本题有十个测试点。十个测试点的数据规模如下：<br/><br/>
编号 N M 出现过的颜色的总数 <br/><br/>
1 1000 0 &lt;=10 <br/><br/>
2 2000 0 &lt;=2000 <br/><br/>
3 5000 0 &lt;=5000 <br/><br/>
4 7000 5 &lt;=7000 <br/><br/>
5 9000 10 &lt;=9000 <br/><br/>
6 10000 100 &lt;=10000 <br/><br/>
7 10000 10000 &lt;=50 <br/><br/>
8 12000 10000 &lt;=12000 <br/><br/>
9 12000 12000 &lt;=12000 <br/><br/>
10 12000 12000 &lt;=12000</p><br/>
<p>　　另外，对于所有数据，有：<br/><br/>
　　1 &lt;= ai &lt;= N, 1 &lt;= bi &lt;= N, 1 &lt;= xi &lt;= N;<br/><br/>
　　1&lt;=wi&lt;=10000<br/><br/>
　　1 &lt;= ci &lt;= 10^9, 1 &lt;= yi &lt;= 10^9<br/><br/>
 </p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=2012国家集训队Round 1 day3">2012国家集训队Round 1 day3</a></p></div>

