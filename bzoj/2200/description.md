
# Description

<div class="content">
Farmer John正在一个新的销售区域对他的牛奶销售方案进行调查。他想把牛奶送到T个城镇 (1 &lt;= T &lt;= 25,000)，编号为1T。这些城镇之间通过R条道路 (1 &lt;= R &lt;= 50,000，编号为1到R) 和P条航线 (1 &lt;= P &lt;= 50,000，编号为1到P) 连接。每条道路i或者航线i连接城镇A_i (1 &lt;= A_i &lt;= T)到B_i (1 &lt;= B_i &lt;= T)，花费为C_i。对于道路，0 &lt;= C_i &lt;= 10,000;然而航线的花费很神奇，花费C_i可能是负数(-10,000 &lt;= C_i &lt;= 10,000)。道路是双向的，可以从A_i到B_i，也可以从B_i到A_i，花费都是C_i。然而航线与之不同，只可以从A_i到B_i。事实上，由于最近恐怖主义太嚣张，为了社会和谐，出台
了一些政策保证：如果有一条航线可以从A_i到B_i，那么保证不可能通过一些道路和航线从B_i回到A_i。由于FJ的奶牛世界公认十分给力，他需要运送奶牛到每一个城镇。他想找到从发送中心城镇S(1 &lt;= S &lt;= T) 把奶牛送到每个城镇的最便宜的方案，或者知道这是不可能的。

</div>

# Input

<div class="content">* 第1行：四个空格隔开的整数: T, R, P, and S

* 第2到R+1行：三个空格隔开的整数（表示一条道路）：A_i, B_i 和 C_i

* 第R+2到R+P+1行：三个空格隔开的整数（表示一条航线）：A_i, B_i 和 C_i

</div>

# Output

<div class="content">* 第1到T行：从S到达城镇i的最小花费，如果不存在输出&#34;NO PATH&#34;。
</div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
6 3 3 4<br/>
1 2 5<br/>
3 4 5<br/>
5 6 10<br/>
3 5 -100<br/>
4 6 -100<br/>
1 3 -10<br/>
<br/>
样例输入解释：<br/>
<br/>
一共六个城镇。在1-2，3-4，5-6之间有道路，花费分别是5，5，10。同时有三条航线：3-&gt;5，<br/>
4-&gt;6和1-&gt;3，花费分别是-100，-100，-10。FJ的中心城镇在城镇4。<br/>
<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
NO PATH<br/>
NO PATH<br/>
5<br/>
0<br/>
-95<br/>
-100<br/>
<br/>
样例输出解释：<br/>
<br/>
FJ的奶牛从4号城镇开始，可以通过道路到达3号城镇。然后他们会通过航线达到5和6号城镇。<br/>
但是不可能到达1和2号城镇。<br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

