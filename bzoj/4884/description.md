
# Description

<div class="content"><div>太空猫(SpaceCat)是一款画面精致、玩法有趣的休闲游戏，你需要控制一只坐在迷你飞碟上的猫咪在太空里不断探</div>
<div>索，让大家看看你能飞得多远。游戏地图可以看成一个二维的网格图，上下是两段障碍物。在游戏的一开始，太空</div>
<div>猫位于地图最左边的下边界之上，且重力方向向下。</div>
<div></div>
<div>在每个时刻，你可以用手指点击屏幕，翻转重力的方向，或者通过遥感控制太空猫往左或往右移动。每次翻转重力</div>
<div>方向时，你需要消耗的能量值等于上下底边之间的高度差。在左右移动的时候，太空猫可以下降到对应重力方向更</div>
<div>低的位置，但不能往上爬。当然，太空猫也不能穿墙而过。在重力翻转的过程中，直到碰到地面之前，你都不能操</div>
<div>控太空猫左右移动。太空猫的终点位于地图的最右端的下底边之上，请计算为了让太空猫到达终点，需要消耗能量</div>
<div>的最小值。</div>
<div><img src="/source/bzoj/4884/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTcwNS92djEuanBn.jpg" width="189" height="211" alt=""/></div></div>

# Input

<div class="content"><div>第一行包含一个正整数n(1&lt;=n&lt;=100000)，即地图的宽度。</div>
<div>第二行包含n个正整数c_1,c_2,...,c_n(2&lt;=c_i&lt;=10^9)，分别表示每个横坐标对应的上边界的高度。</div>
<div>第三行包含n个正整数f_1,f_2,...,f_n(1&lt;=f_i&lt;c_i)，分别表示每个横坐标对应的下边界的高度。</div></div>

# Output

<div class="content"><div>输出一行一个整数，即最少的能量，若无法到达终点，请输出“-1”。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
3 4 3 2<br/>
1 2 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">4</span></div>

# Hint

<div class="content"><p></p><p> “在左右移动的时候，太空猫【可以】下降到对应重力方向更低的位置”</p><br/>
<div>应改为 “太空猫【会】下降到对应重力方向更低的位置”</div><br/>
<div>就是说，太空猫在能往下掉的时候不能选择直接飞过去</div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获得">本OJ付费获得</a></p></div>

