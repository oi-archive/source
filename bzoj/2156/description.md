
# Description

<div class="content"><p>众所周知，新世纪的科学很发达，于是Ray 和Raven 开始了星际探险，他们在宇宙中开辟了一片空间，建造了N 个空间站。这N 个空间站由一些单向的时空隧道连接，这些时空隧道都有一个穿越指数，穿过这些时空隧道，你可以走到未来或者回到过去，当然，这些都是由穿越指数决定的。有一天，Ray 和Raven 开始了一场比赛。他们要从一个空间站S 出发去另一个空间站T，先到的人获胜。Raven 一定会选一条能最快到达T 的路线。他希望Ray 输给他，所以事先在Ray 的飞船上设定了飞行路径，使得Ray 从S 到T 只能走一条特定的路径。但是，Ray 有对策，他有一台能够操纵时空隧道的机器，这台机器每次可以把某一条时空隧道的穿越指数增加或减少1，但是因为操纵机器很累，所以Ray 希望尽可能少改动，当然，如果改动后从某个空间站经过一系列的穿越可以在从这个空间站出发之前回到这个空间站，那么这样的改动是不允许的。修改之后，Raven 依然会走能最快到达终点的路线，所以Ray 是不可能赢的。但他请你帮助他确定改动时空隧道的方案，使得他能和Raven 同时到达T。</p></div>

# Input

<div class="content"><p>输入的第一行包含两个整数N 和M，代表空间站的数目和时空隧道的数目。接下来M 行，每行三个整数u、v 和w，代表从空间站u 到空间站 v 有一条时空隧道，它的穿越指数是w。0 &lt;= w &lt;= 2000。空间站的编号是0 : : :N − 1。第M + 2 行包含一个整数p，代表Raven 在Ray 的飞船上设定的那条路径的空间站数。p &lt;= N。第M + 3 行包含p 个互不相同的数，表示那条路径上的空间站的编号，第一个数是S，最后一个数是T。</p></div>

# Output

<div class="content"><p>输出的第一行包含一个整数，表示Ray 走那条路径并且能够赢得比赛的情况下操纵时间机器的最小次数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 3<br/>
0 1 1<br/>
1 2 2<br/>
0 2 1<br/>
30<br/>
1 2</span></div>

# Sample Output

<div class="content"><span class="sampledata">2</span></div>

# Hint

<div class="content"><p></p><p>一共有10 个数据，对于第i (1 &lt;= i &lt;= 10) 个数据， N = i * 500， M = i * 5000。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

