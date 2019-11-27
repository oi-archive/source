<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>OI island是一个非常漂亮的岛屿,自开发以来,到这儿来旅游的人很多。然而，由于该岛屿刚刚开发不久，所以那里的交通情况还是很糟糕。所以，OIER Association组织成立了，旨在建立OI island的交通系统。 OI island有n个旅游景点，不妨将它们从1到n标号。现在，OIER Association需要修公路将这些景点连接起来。一条公路连接两个景点。公路有，不妨称它们为一级公路和二级公路。一级公路上的车速快，但是修路的花费要大一些。 OIER Association打算修n-1条公路将这些景点连接起来（使得任意两个景点之间都会有一条路径）。为了保证公路系统的效率, OIER Association希望在这n-1条公路之中,至少有k条(0≤k≤n-1)一级公路。OIER Association也不希望为一条公路花费的钱。所以，他们希望在满足上述条件的情况下，花费最多的一条公路的花费尽可能的少。 而你的任务就是，在给定一些可能修建的公路的情况下，选择n-1条公路，满足上面的条件。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>第一行有三个数n,k,m，这些数之间用空格分开。 N和k如前所述，m表示有m对景点之间可以修公路。以下的m行，每一行有4个正整数a,b,c1,c2表示在景点a与b 之间可以修公路,如果修一级公路,则需要c1的花费,如果修二级公路,则需要c2的花费。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>一个数据，表示花费最大的公路的花费。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<pre>4 2 5
1 2 6 5
1 3 3 1
2 3 9 4
2 4 6 1
3 4 4 2</pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1≤n≤10000，0≤k≤n-1，n-1≤m≤20000，1≤a,b≤n,a≠b,1≤c2≤c1≤30000</p>
</div>
</div>