
# Description

<div class="content"><p><span style="font-size: medium">为了便于牛们欣赏和锻炼，农夫JOHN在他的农场上新添加了一个美丽的池塘。 JOHN的池塘是一个长方形，他已经把它划分成了M行N列的小正方行 (1 &lt;= M &lt;= 30; 1 &lt;= N &lt;= 30). 某些正方行里是石头，另外一些则是特别结实的荷叶，其余则只有清水。 为了锻炼，Bessie想从一片荷叶跳到另外一片。她的每一次跳跃都是一个象棋中的马步：两行一列或一行两列。 JOHN看到了Bessie并且发现有时Bessie没有办法达到她的目标荷叶。他准备添加一些荷叶来让Bessie完成她的目标。当然，荷叶不能放在石头上。 帮助JOHN找出他最少要放多少片荷叶和他一共有多少种放最少片荷叶的方案。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">第1行： 两个整数， M 和 N。</span></p>
<p><span style="font-size: medium">第2~M+1行： 第i+1包含N个数，分别为第i行的N个格子的情况。 0表示格子为空，1表示有一片荷叶，2表示格子里有石头，3表示此格子是Bessie的起点，4 表示此格子是Bessie的目标。 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">第1行： 一个数，最少情况下需要添加的荷叶数目。如果没有方案存在，输出- 1。</span></p>
<p><span style="font-size: medium">第2行： 一个数，达到最小值的方案总数。这个数保证不超过内设64位整数(long long/ int64)的大小。如果第一行是-1，不要输出此行。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">4 5<br/>
1 0 0 0 0<br/>
3 0 0 0 0<br/>
0 0 2 0 0<br/>
0 0 0 4 0<br/>
<br/>
输入解释：<br/>
池塘含4行5列。Bessie在第2行第1列并且想跳到第4行第4列。池塘里有1块<br/>
石头和3片荷叶。<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
3<br/>
<br/>
输出解释：<br/>
<br/>
至少需要2片荷叶。一共有三种摆法：<br/>
	第4行第2列，第2行第3列<br/>
	第1行第3列，第3行第2列<br/>
	第1行第3列，第2行第5列<br/>
<br/>
          R1C2,R2C3     R1C3,R3C2     R1C3,R2C5<br/>
          1 0 0 0 0     1 0 X 0 0     1 0 X 0 0<br/>
          3 0 X 0 0     3 0 0 0 0     3 0 0 0 X<br/>
          0 0 2 0 0     0 X 2 0 0     0 0 2 0 0<br/>
          0 X 0 4 0     0 0 0 4 0     0 0 0 4 0<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

