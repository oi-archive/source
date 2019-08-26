
# Description

<div class="content"><div>A国有N座城市，依次标为1到N。同时，在这N座城市间有M条单向道路，每条道路的长度是一个正整数。现在，A国</div>
<div>交通部指定了一条从城市1到城市N的路径，并且保证这条路径的长度是所有从城市1到城市N的路径中最短的。不幸</div>
<div>的是，因为从城市1到城市N旅行的人越来越多，这条由交通部指定的路径经常发生堵塞。现在A国想知道，这条路</div>
<div>径中的任意一条道路无法通行时，由城市1到N的最短路径长度是多少。</div></div>

# Input

<div class="content"><div>第一行是三个用空格分开的正整数N、M和L，分别表示城市数目、单向道路数目和交通部指定的最短路径包含多少条道路。</div>
<div>按下来M行，每行三个用空格分开的整数a、b和c，表示存在一条由城市a到城市b的长度为c的单向道路。</div>
<div>这M行的行号也是对应道路的编号，即其中第1行对应的道路编号为1，第2行对应的道路编号为2，…，第M行对应的道路编号为M。</div>
<div>最后一行为L个用空格分开的整数sp(1)…，，sp(L)，依次表示从城市1到城市N的由交通部指定的最短路径上的道路的编号。</div>
<div>2&lt;N&lt;100000，1&lt;M&lt;200000。所用道路长度大于0小于10000。</div>
<p></p></div>

# Output

<div class="content"><div>L行，每行为一个整数，第i行(i=1，2…，，L)的整数表示删去编号为sp(i)的道路后从城市1到城市N的最短路径长度。</div>
<div>如果去掉后没有从城市1到城市N的路径，则输出一1。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 5 2<br/>
1 2 2<br/>
1 3 2<br/>
3 4 4<br/>
3 2 1<br/>
2 4 3<br/>
1 5<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
6<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">数据已加强By Vfleaking，另2017.9.1再加数据一组，未重测。</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

