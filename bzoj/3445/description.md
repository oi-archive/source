
# Description

<div class="content"><p><span style="font-family: 宋体;">有一个无向图，共</span><span lang="EN-US">N</span><span style="font-family: 宋体;">个节点，编号</span><span lang="EN-US">1</span><span style="font-family: 宋体;">至</span><span lang="EN-US">N</span><span style="font-family: 宋体;">，共</span><span lang="EN-US">M</span><span style="font-family: 宋体;">条边。</span><span lang="EN-US">FJ</span><span style="font-family: 宋体;">在节点</span><span lang="EN-US">1</span><span style="font-family: 宋体;">，它想到达节点</span><span lang="EN-US">N</span><span style="font-family: 宋体;">。</span><span lang="EN-US">FJ</span><span style="font-family: 宋体;">总是会选择最短路径到达节点</span><span lang="EN-US">N</span><span style="font-family: 宋体;">。作为捣蛋的奶牛</span><span lang="EN-US">Bessie</span><span style="font-family: 宋体;">，它想尽量延迟</span><span lang="EN-US">FJ</span><span style="font-family: 宋体;">到达节点</span><span lang="EN-US">N</span><span style="font-family: 宋体;">的时间，于是</span><span lang="EN-US">Bessie</span><span style="font-family: 宋体;">决定从</span><span lang="EN-US">M</span><span style="font-family: 宋体;">条边之中选择某一条边，使得改边的长度变成原来的两倍，由于智商的问题，</span><span lang="EN-US">Bessie</span><span style="font-family: 宋体;">不知道选择加倍哪条边的长度才能使得</span><span lang="EN-US">FJ</span><span style="font-family: 宋体;">到达</span><span lang="EN-US">N</span><span style="font-family: 宋体;">号节点的时间最迟。注意：不管</span><span lang="EN-US">Bessie</span><span style="font-family: 宋体;">选择加倍哪条边的长度，</span><span lang="EN-US">FJ</span><span style="font-family: 宋体;">总是会从</span><span lang="EN-US">1</span><span style="font-family: 宋体;">号节点开始走最短路径到达</span><span lang="EN-US">N</span><span style="font-family: 宋体;">号点。</span><span lang="EN-US"> </span></p></div>

# Input

<div class="content"><p><span lang="EN-US"> </span><span style="font-family: 宋体;">第一行，两个整数</span><span lang="EN-US">N</span><span style="font-family: 宋体;">和</span><span lang="EN-US">M. 1 &lt;=N&lt;=250, 1&lt;=M&lt;=250000</span><span style="font-family: 宋体;">。</span><span lang="EN-US"> </span></p>
<p class="MsoNormal"><span lang="EN-US"> </span><span style="font-family: 宋体;">接下来有</span><span lang="EN-US">M</span><span style="font-family: 宋体;">行，每行三个整数：</span><span lang="EN-US">A</span><span style="font-family: 宋体;">，</span><span lang="EN-US">B</span><span style="font-family: 宋体;">，</span><span lang="EN-US">L</span><span style="font-family: 宋体;">，表示节点</span><span lang="EN-US">A</span><span style="font-family: 宋体;">和节点</span><span lang="EN-US">B</span><span style="font-family: 宋体;">之间有一条长度为</span><span lang="EN-US">L</span><span style="font-family: 宋体;">的无向边。</span><span lang="EN-US">1&lt;=L&lt;=1000000</span><span style="font-family: 宋体;">。</span><span lang="EN-US"> </span></p></div>

# Output

<div class="content"><p><span lang="EN-US">  </span><span style="font-family: 宋体;">一个整数。</span><span lang="EN-US">Bessie</span><span style="font-family: 宋体;">选择了加倍某一条边的长度后，奶牛</span><span lang="EN-US">FJ</span><span style="font-family: 宋体;">从节点</span><span lang="EN-US">1</span><span style="font-family: 宋体;">到达节点</span><span lang="EN-US">N</span><span style="font-family: 宋体;">的最短路径是多少。但是输出的格式有变化，假设</span><span lang="EN-US">Bessie</span><span style="font-family: 宋体;">没有加倍某一条边的长度之前，</span><span lang="EN-US">FJ</span><span style="font-family: 宋体;">从</span><span lang="EN-US">1</span><span style="font-family: 宋体;">号节点到达</span><span lang="EN-US">N</span><span style="font-family: 宋体;">号节点的最短路径是</span><span lang="EN-US">X</span><span style="font-family: 宋体;">；在</span><span lang="EN-US">Bessie</span><span style="font-family: 宋体;">加倍某一条边的长度之后，</span><span lang="EN-US">FJ</span><span style="font-family: 宋体;">从</span><span lang="EN-US">1</span><span style="font-family: 宋体;">号节点到达</span><span lang="EN-US">N</span><span style="font-family: 宋体;">号节点的最短路径是</span><span lang="EN-US">Y</span><span style="font-family: 宋体;">，那么你输出的结果是</span><span lang="EN-US">Y-X</span><span style="font-family: 宋体;">。</span><span lang="EN-US"> </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">5 7<br/>
2 1 5<br/>
1 3 1<br/>
3 2 8<br/>
3 5 7<br/>
3 4 3<br/>
2 4 7<br/>
4 5 2<br/>
INPUT DETAILS: There are 5 fields and 7 pathways. Currently, the shortest path from the house (field 1) to the barn (field 5) is 1-3-4-5 of total length 1+3+2=6. </span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
（把节点3到节点4的边从原来的长度3变成长度6）   </span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

