
# Description

<div class="content">Bessie正在计划一年一度的奶牛大集会，来自全国各地的奶牛将来参加这一次集会。当然，她会选择最方便的地点来举办这次集会。每个奶牛居住在 N(1&lt;=N&lt;=100,000) 个农场中的一个，这些农场由N-1条道路连接，并且从任意一个农场都能够到达另外一个农场。道路i连接农场A_i和B_i(1 &lt;= A_i &lt;=N; 1 &lt;= B_i &lt;= N),长度为L_i(1 &lt;= L_i &lt;= 1,000)。集会可以在N个农场中的任意一个举行。另外，每个牛棚中居住者C_i(0 &lt;= C_i &lt;= 1,000)只奶牛。在选择集会的地点的时候，Bessie希望最大化方便的程度(也就是最小化不方便程度)。比如选择第X个农场作为集会地点，它的不方便程度是其它牛棚中每只奶牛去参加集会所走的路程之和，(比如，农场i到达农场X的距离是20，那么总路程就是C_i*20)。帮助Bessie找出最方便的地点来举行大集会。
考虑一个由五个农场组成的国家，分别由长度各异的道路连接起来。在所有农场中，3号和4号没有奶牛居住。
<img border="0" src="/source/bzoj/1827/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE4MjcuanBn.jpg"/> </div>

# Input

<div class="content">第一行：一个整数N

* 第二到N+1行：第i+1行有一个整数C_i

* 第N+2行到2*N行，第i+N+1行为3个整数：A_i,B_i和L_i。

</div>

# Output

<div class="content">* 第一行：一个值，表示最小的不方便值。

</div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1<br/>
1<br/>
0<br/>
0<br/>
2<br/>
1 3 1<br/>
2 3 2<br/>
3 4 3<br/>
4 5 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">15<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

