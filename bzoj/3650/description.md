
# Description

<div class="content"><p><span style="font-size: medium">ZTY想要环游世界！他会驾驶一架飞机沿着赤道顺时针飞行一周。现在他手头有S架飞机，每架飞机的油箱都有自己的容量限制Di，表示在飞机的油箱装满的情况下，最远可以飞行多远。赤道上有n座城市，相邻两座城市间有一定的距离。ZTY有很多钱，所以你可以不用考虑加油的问题，只需要认为降落到每座城市都可以把飞机的油箱加满。ZTY想要尽快完成环游世界的目标，所以他想要飞机降落的次数尽量少。那么ZTY就想要问你：对每架飞机，最少降落多少次才可以完成环游世界的任务？注意：ZTY可以选择任意一个城市作为他的起点。另外，最后回到起点也需要算一次降落。<br/>
</span></p></div>

# Input

<div class="content"><p><br/>
<font size="4">第一行两个整数，表示n与s。<br/>
接下来一行n个整数，第i个整数表示第i个城市与第i+1个城市间的距离（第n个整数表示第n个城市与第1个城市间的距离）。<br/>
接下来s个整数，第i个整数表示第i架飞机的容量限制Di。</font></p>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium">对 s 架飞机每架飞机输出一行。如果 ZTY 使用这架飞机不可能完成环游世界的目标，输出“NO”。否则输出 ZTY最少需要降落多少次。 </span></p>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
6 4 <br/>
2 2 1 3 3 1 <br/>
3 2 4 11 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
8 3 <br/>
2 2 2 2 2 2 2 2 <br/>
1 16 2 <br/>
<br/>
<br/>
</span></div>

# Hint

<div class="content"><p></p><p><span style="font-size: medium">样例 1 解释： <br/><br/>
对第一架飞机，可以按 6-&gt;2-&gt;4-&gt;5-&gt;6的顺序来飞行。 <br/><br/>
对第二架飞机，显然它不能越过 4与 5 之间3的距离。 <br/><br/>
 </span></p><br/>
<p><span style="font-size: medium">对 100%的数据 n 不超过 1000000，s 不超过 100。赤道长度（所有距离和）不超过10^9。所有输入小于2^31。 <br/><br/>
   <br/><br/>
</span></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

