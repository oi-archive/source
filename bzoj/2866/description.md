
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">从前有个美丽的C国，在C国中，有n个城市，m条单向的公路。对于一个城市u，有一个固定的贸易输出额f[u]。对于两个城市u和v，如果从u有路径到v，且从v有路径到u，则我们称u、v为一对互利城市。对于每一对互利的城市u、v，如果存在一条公路&lt;x，y&gt;，满足u有路径到x，y有路径到v，我们则称这条公路&lt;x，y&gt;为u到v的重要公路。而每一对互利城市u、v，u都会向每一条u到v的重要公路上输送贸易额为f[u]的货物，同样的v也会向每一条v到u的重要公路输送贸易额为f[v]的货物。一个城市最多在一条公路上输送1次货物，换言之，一个城市u对一条公路的贡献，非f[u]即0。对于每一条公路来说，这条公路的重要程度就是这条公路上货物的贸易额的总和。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">现在C国的国王想要选出一些城市，建立城市群。一个城市群就是一个城市的集合，这个城市群的繁荣程度为，所有两端点都是这个城市群中的城市的公路，的重要程度和。当然啦，如果就以城市群的繁荣程度来评判一个城市群似乎不太公平，极易导致地方割据的长生。于是乎聪明的C国国王就想到了平均繁荣程度的概念，一个城市群的平均繁荣程度为，这个城市群的繁荣程度与这个城市群城市个数的比值。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">现在C国的国王想知道，在他国家里，平均繁荣程度最高的城市群的平均繁荣程度为多少。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div style="text-indent: 20.25pt"><span style="font-size: medium">第一行两个数n和m，n个城市的标号为1到n。</span></div>
<div style="text-indent: 20.25pt"><span style="font-size: medium">第二行n个数表示，每个城市的贸易输出额。</span></div>
<div style="text-indent: 20.25pt"><span style="font-size: medium">接下来m行每行两个数x、y，表示一条公路从x到y。</span></div>
<div style="text-indent: 20.25pt"><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div> </div>
<div style="text-indent: 20.25pt"><span style="font-size: medium">一行一个数，表示最大的平均繁荣程度，保留两位小数。</span></div>
<div style="text-indent: 20.25pt"><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
2 2<br/>
1 2<br/>
1 2<br/>
2 1<br/>
 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3.00<br/>
 <br/>
</span></div>

# Hint

<div class="content"><p></p><p>对于100%的数据n &lt;= 300，m &lt;= n*n</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

