
# Description

<div class="content"><p><span style="font-size: medium">小宇从历史书上了解到一个古老的文明。这个文明在各个方面高度发达，交通方面也不例外。考古学家已经知道，这个文明在全盛时期有n座城市，编号为1..n。m条道路连接在这些城市之间，每条道路将两个城市连接起来，使得两地的居民可以方便地来往。一对城市之间可能存在多条道路。<br/>
据史料记载，这个文明的交通网络满足两个奇怪的特征。首先，这个文明崇拜数字K，所以对于任何一条道路，设它连接的两个城市分别为u和v，则必定满足1 &lt;=|u - v| &lt;= K。此外，任何一个城市都与恰好偶数条道路相连（0也被认为是偶数）。不过，由于时间过于久远，具体的交通网络我们已经无法得知了。小宇很好奇这n个城市之间究竟有多少种可能的连接方法，于是她向你求助。<br/>
方法数可能很大，你只需要输出方法数模1000000007后的结果。<br/>
</span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">输入共一行，为3个整数n，m，K。<br/>
</span></p></div>

# Output

<div class="content"><p><font size="4">输出1个整数，表示方案数模1000000007后的结果。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">【输入样例1】<br/>
3 4 1<br/>
【输入样例2】<br/>
4 3 3<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">【输出样例1】<br/>
3<br/>
<br/>
【输出样例2】<br/>
4<br/>
【数据规模】<br/>
</span></div>

# Hint

<div class="content"><p></p><p>100%的数据满足1<br/><br/>
&lt;= n &lt;= 30, 0 &lt;= m &lt;= 30, 1 &lt;= K &lt;= 8.<br/><br/>
【题目说明】<br/><br/>
两种可能的连接方法不同当且仅当存在一对城市，它们间的道路数在两种方法中不同。<br/><br/>
在交通网络中，有可能存在两个城市无法互相到达。</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

