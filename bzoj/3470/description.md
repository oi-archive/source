
# Description

<div class="content"><p><span style="font-size: medium">雨后的Poetic Island空气格外清新，于是Freda和Rainbow出来散步。 Poetic Island的交通可以看作一张n个点、m 边的有向无环图。由于刚下过雨，每条边都有一个积水深度，而恰好Freda 和Rainbow都喜欢踩水玩儿，于是Ta们从某个点出发，选择走向哪条边的概率与该边的积水深度是成正比的。即：如果Freda和Rainbow现在在点u，点u 出发的所有边的积水深度之和为s，从u到v的边积水深度为w，那么Ta们选择走向v的概率就是 w/s。  <br/>
Ta们会一直走下去，直到到达一个没有出边的点，那么散步的路程长度就是走过的边的数量。更特殊的是，Freda和Rainbow在出发之前还可以选择一条边，在散步过程中无视这条边的存在（当然也可以不选择）。请你帮忙计算一下，Ta 们从0号点出发，散步的路程长度的期望值最大是多少？  <br/>
 <br/>
 <br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">第一行两个正整数 n、m。 <br/>
接下来m行每行三个整数u、v、w，表示从u到v有一条无向边，积水深度为w。 <br/>
 <br/>
 <br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font size="4">输出Freda和Rainbow散步的路程长度的最大期望值，四舍五入保留六位小数。</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 <br/>
0 1 2 <br/>
0 2 1 <br/>
0 3 3 <br/>
1 3 1 <br/>
2 3 4 </span></div>

# Sample Output

<div class="content"><span class="sampledata">2.000000 </span></div>

# Hint

<div class="content"><p></p><p>对于  100% 的数据，2&lt;=n&lt;=10000，1&lt;=m&lt;=100000，0&lt;=u,v&lt;n，1&lt;=w&lt;=1000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Adera 2 杯省选模拟赛">Adera 2 杯省选模拟赛</a></p></div>

