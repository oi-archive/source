
# Description

<div class="content"><div style="text-indent: 24pt" align="left"><span style="font-size: 12pt">给出一个</span><i><span style="font-size: 12pt">N</span></i><span style="font-size: 12pt">个点</span><i><span style="font-size: 12pt">M</span></i><span style="font-size: 12pt">条边的无向带权图，以及</span><i><span style="font-size: 12pt">Q</span></i><span style="font-size: 12pt">个询问，每次询问在图中删掉一条边后图的最小生成树。</span><span style="font-size: 12pt">(</span><span style="font-size: 12pt">各询问间独立，每次询问不对之后的询问产生影响，即被删掉的边在下一条询问中依然存在</span><span style="font-size: 12pt">)</span></div>
<div style="text-indent: 21.6pt"> </div></div>

# Input

<div class="content"><div style="text-indent: 24pt"><span style="font-size: 12pt">第一行两个正整数N,M(N&lt;=50000,M&lt;=100000)表示原图的顶点数和边数。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">下面M行，每行三个整数X,Y,W描述了图的一条边(X,Y)，其边权为W（W&lt;=10000）。保证两点之间至多只有一条边。</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">接着一行一个正整数Q，表示询问数。(1&lt;=Q&lt;=100000)</span></div>
<div style="text-indent: 24pt"><span style="font-size: 12pt">下面Q行，每行一个询问，询问中包含一个正整数T，表示把编号为T的边删掉(边从1到M按输入顺序编号)。</span></div>
<div style="text-indent: 24pt"> </div></div>

# Output

<div class="content"><div style="text-indent: 30pt"><span style="font-size: 12pt">Q</span><span style="font-size: 12pt">行，对于每个询问输出对应最小生成树的边权和的值，如果图不连通则输出</span><span style="font-size: 12pt">“Not connected”</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 4<br/>
1 2 3 <br/>
1 3 5 <br/>
2 3 9 <br/>
2 4 1 <br/>
4 <br/>
1 <br/>
2 <br/>
3 <br/>
4<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">15 <br/>
13 <br/>
9 <br/>
Not connected<br/>
 <br/>
样例解释:<br/>
无<br/>
 <br/>
数据规模：<br/>
10%的数据N,M,Q&lt;=100。<br/>
另外30%的数据，N&lt;=1000<br/>
100%的数据如题目。</span></div>

# Hint

<div class="content"><p></p><p> 更新数据---2015.6.9</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

