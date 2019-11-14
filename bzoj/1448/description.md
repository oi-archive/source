
# Description

<div class="content">有一串由n珠子构成的环形珠链。珠链上的每个珠子要么黑色要么白色。每个珠子都能感应到它左边的k个珠子以及右边的k个珠子。每一秒珠子都会尝试改变自己的颜色，对于一个珠子，如果它感应到的2k个珠子中有奇数个是黑色，那么它会改变自己的颜色，否则它会保持自己原来的状态。并且所有要改变颜色的珠子都会在同一时刻改变自己的颜色。由于珠链是环形的，因此，对于两条珠链，如果其中一条可以通过旋转变成另外一条，那么这两条珠链是本质相同的。给出n、k、t以及一条长度为n的珠链的珠子的颜色，问有多少条本质不同的珠链能够在t秒之后变成给出的珠链。

<img border="0" src="/source/bzoj/1448/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE0NDguanBn.jpg"/>
</div>

# Input

<div class="content">第一行给出数据组数
下面每组数据,先给出N,K,T
再一行给出珠子的描述</div>

# Output

<div class="content">给出有多少组不同的形态,答案mod 9973</div>

# Sample Input

<div class="content"><span class="sampledata">3 <br/>
6 1 1 <br/>
bbbwww <br/>
6 1 1 <br/>
bwbbww <br/>
12 2 1 <br/>
bbwwwbwwwwww </span></div>

# Sample Output

<div class="content"><span class="sampledata">4 <br/>
0 <br/>
1 </span></div>

# Hint

<div class="content"><p>数据范围：1&lt;= n&lt;=  200, 1&lt;= k&lt;=  (n - 1) / 2, 0&lt;=  t &lt;= 200，有多组数据，数据组数不多于20。<br/>
</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

