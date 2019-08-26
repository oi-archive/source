
# Description

<div class="content"><div>给定N个数对(S_i,T_i)，表示时刻S_i时在位置T_i处出现一粒糖果。有一些机器人可供使用，每个机器人可花费一</div>
<div>单位时间向相邻位置移动。要求用最少的机器人接到全部糖果。时刻0时机器人位置可自行安排。</div>
<div>1≤N≤100000， </div>
<div>0≤S_i,T_i≤10^9。</div></div>

# Input

<div class="content"><p> <span style="font-family: arial, verdana, helvetica, sans-serif;">第一行包含一个整数 n，表示该轮生产所产生的糖果数量。</span><br style="font-family: arial, verdana, helvetica, sans-serif;"/>
<span style="font-family: arial, verdana, helvetica, sans-serif;">接下来的 n 行中，第 i 行包含两个整数 s_i 和 t_i，表示第 i 个糖果的产生位置和时间。</span></p></div>

# Output

<div class="content"></div>

# Sample Input

<div class="content"><span class="sampledata">5<br/>
1 1<br/>
2 3<br/>
1 5<br/>
3 4<br/>
2 6</span></div>

# Sample Output

<div class="content"><span class="sampledata">2<br/>
样例解释：<br/>
在时刻1的时候，有两个糖果在不同的位置掉下，因此需要两个机器人分别赶到位置1和位置5<br/>
在时刻2的时候，也有两个糖果在不同的位置掉下，因此需要两个机器人分别赶到位置3和位置6<br/>
在时刻3的时候，只有一个糖果掉下，因此需要一个机器人赶到位置4<br/>
所以对于5颗糖果需要的机器人编号分别为1 1 2 1 2</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

