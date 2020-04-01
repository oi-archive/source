
# Description

<div class="content">战犯们企图逃离监狱，他们详细地计划了如何逃出监狱本身，逃出监狱之后他们希望在附近的一个村子里找到掩护。村子（下图中的B）和监狱（图中的A）中间有一个峡谷，这个峡谷也是有士兵守卫的。守卫峡谷的士兵们坐在岗哨上很少走动，每个士兵的观察范围是100米。士兵所处位置决定了战犯们能否安全通过峡谷，安全通过的条件就是在任何时刻战犯们距离最近的士兵大于100米。
给定峡谷的长、宽和每个士兵在峡谷中的坐标，假定士兵的位置一直保持不变，请你写一个程序计算战犯们能否不被士兵发现，顺利通过峡谷。如果不能，那么战犯们最少需要消灭几个士兵才能安全通过峡谷（无论士兵是否被另一个士兵看到，他都可以被消灭）。

<img border="0" src="/source/bzoj/1340/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvaW1hZ2VzLzEzNDAuanBn.jpg"/>
</div>

# Input

<div class="content">第一行有三个整数L、W和N，分别表示峡谷的长度、宽度和士兵的人数。接下来的N行，每行两个整数Xi和Yi，表示第i个士兵在峡谷的坐标（0 &lt;= Xi &lt;= L, 0 &lt;= Yi &lt;= W)，坐标以米为单位，峡谷的西南角坐标为(0, 0)，东北角坐标为(L, W)，见上图。注意：通过峡谷可以从(0, ys)（0 &lt;= ys  &lt;= W）到（L, ye）（0 &lt;= ye &lt;= W），其中ys， ye不一定是整数。
</div>

# Output

<div class="content">只有一行，为一个整数，即安全通过峡谷需要消灭的士兵的人数，如果不需要消灭任何士兵，则输出0。
</div>

# Sample Input

<div class="content"><span class="sampledata">130 340 5<br/>
10 50<br/>
130 130<br/>
70 170<br/>
0 180<br/>
60 260<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1</span></div>

# Hint

<div class="content"><p>1 &lt;= W &lt;= 50,000 1 &lt;= L &lt;= 50,000 1 &lt;= N &lt;= 250</p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

