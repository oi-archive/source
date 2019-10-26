
# Description

<div class="content">每天Farmer John的N头奶牛(1 &lt;= N &lt;= 100000，编号1…N)从粮仓走向他的自己的牧场。牧场构成了一棵树，粮仓在1号牧场。恰好有N-1条道路直接连接着牧场，使得牧场之间都恰好有一条路径相连。第i条路连接着A_i，B_i，(1 &lt;= A_i &lt;= N; 1 &lt;= B_i &lt;= N)。奶牛们每人有一个私人牧场P_i (1 &lt;= P_i &lt;= N)。粮仓的门每次只能让一只奶牛离开。耐心的奶牛们会等到他们的前面的朋友们到达了自己的私人牧场后才离开。首先奶牛1离开，前往P_1；然后是奶牛2，以此类推。当奶牛i走向牧场P_i时候，他可能会经过正在吃草的同伴旁。当路过已经有奶牛的牧场时，奶牛i会放慢自己的速度，防止打扰他的朋友。
考虑如下的牧场结构（括号内的数字代表了牧场的所有者）。

<img border="0" src="/source/bzoj/1782/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzE3ODIuanBn.jpg"/> </div>

# Input

<div class="content">* 第1行 :  一个正整数N

* 第2…N行:  第i+1行包括一对正整数A_i,B_i

* 第N+1..N+N行: 第 N+i行 包括一个正整数: P_i

</div>

# Output

<div class="content">* 第一行到第N行：第i行表示第i只奶牛需要被放慢的次数

</div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 4<br/>
5 4<br/>
1 3<br/>
2 4<br/>
4<br/>
2<br/>
1<br/>
5<br/>
3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">0<br/>
1<br/>
0<br/>
2<br/>
1<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

