
# Description

<div class="content"><p><span style="font-size: medium; ">Farmer Ron in Colorado is building a ski resort for his cows (though budget constraints dictate construction of just one ski lift). The lift will be constructed as a monorail and will connect a concrete support at the starting location to the support at the ending location via some number of intermediate supports, each of height 0 above its land. A straight-line segment of steel connects every pair of adjacent supports. For obvious reasons, each section of straight steel must lie above the ground at all points.  Always frugal, FR wants to minimize the number of supports that he must build. He has surveyed the N (2 &lt;= N &lt;= 5,000) equal-sized plots of land the lift will traverse and recorded the integral height H (0 &lt;= H &lt;= 1,000,000,000) of each plot. Safety regulations require FR to build adjacent supports no more than K (1 &lt;= K &lt;= N - 1) units apart. The steel between each pair of supports is rigid and forms a straight line from one support to the next.  Help FR compute the smallest number of supports required such that: each segment of steel lies entirely above (or just tangent to) each piece of ground, no two consecutive supports are more than K units apart horizontally, and a support resides both on the first plot of land and on the last plot of land.</span></p>
<p></p><p class="MsoNormal"><span style="font-size: medium; "><span style="font-family: 宋体; ">科罗拉州的罗恩打算为他的奶牛们建造一个滑雪场，虽然需要的设施仅仅是一部缆车．建造一部缆车，需要从山脚到山顶立若干根柱子，并用钢丝连结它们．你可以认为相对于地面，柱子的高度可以忽略不计．每相邻两根柱子间都有钢丝直接相连．显然，所有钢丝的任何一段都不能在地面之下．</span><span lang="EN-US">    </span><span style="font-family: 宋体; ">为了节省建造的费用，罗恩希望在工程中修建尽可能少的柱子．他在准备修建缆车的山坡上迭定了</span><span lang="EN-US">N(2</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">N</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">5000)</span><span style="font-family: 宋体; ">个两两之间水平距离相等的点，并且测量了每个点的高度</span><span lang="EN-US">H(O</span><span style="font-family: 宋体; ">≤日≤</span><span lang="EN-US">10^9)</span><span style="font-family: 宋体; ">．并且，按照国家安全标准，相邻两根柱子间的距离不能超过</span><span lang="EN-US">K(1</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">K</span><span style="font-family: 宋体; ">≤</span><span lang="EN-US">N-1)</span><span style="font-family: 宋体; ">个单位长度．柱子间的钢丝都是笔直的</span><span lang="EN-US">. </span><span style="font-family: 宋体; ">罗恩希望你帮他计算一下，在满足下列条件的情况下，他至少要修建多少根柱子：首先，所有的柱子都必须修建在他所选定的点上，且每一段钢丝都必须高于地面或者正好跟地面相切．相邻两根柱子的距离不大于</span><span lang="EN-US">K</span><span style="font-family: 宋体; ">个单位长度．当然，在第一个点与最后一个点上一定都要修建柱子．</span></span></p>
<p class="MsoNormal"></p>
<p></p></div>

# Input

<div class="content"><p style="text-align: left; "><span style="font-size: medium; ">* Line 1: Two space-separate integers, N and K  </span></p>
<p style="text-align: left; "><span style="font-size: medium; ">* Lines 2..N+1: Line i+1 contains a single integer that is the height         of plot i.</span></p>
<p></p><div style="text-align: left; "><span style="font-size: medium; "><br/>
</span></div>
<div>
<p class="MsoNormal" style="text-align: left; "><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">第</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">行：两个整数</span><span lang="EN-US">N</span><span style="font-family: 宋体; ">和</span><span lang="EN-US">K</span><span style="font-family: 宋体; ">，用空格隔开．</span></span></p>
<p class="MsoNormal" style="text-align: left; "><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">第</span><span lang="EN-US">2</span><span style="font-family: 宋体; ">到</span><span lang="EN-US">N+1</span><span style="font-family: 宋体; ">行：每行包括一个正整数，第</span><span lang="EN-US">i+l</span><span style="font-family: 宋体; ">行的数描述了第</span><span lang="EN-US">i</span><span style="font-family: 宋体; ">个点的高度．</span></span></p>
<p class="MsoNormal" style="text-align: left; "></p>
<p class="MsoNormal"></p>
</div>
<p></p></div>

# Output

<div class="content"><p><span style="font-size: medium; ">* Line 1: A single integer equal to the fewest number of lift towers         FR needs to  build subject to the above constraints</span></p>
<p></p>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">输出一个整数，即罗恩最少需要修建的柱子的数目．</span></span></p>
<p class="MsoNormal"></p></div>

# Sample Input

<div class="content"><span class="sampledata">13 4<br/>
0<br/>
1<br/>
0<br/>
2<br/>
4<br/>
6<br/>
8<br/>
6<br/>
8<br/>
8<br/>
9<br/>
11<br/>
12</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
</span></div>

# Hint

<div class="content"><p></p><p> <span style="font-family: 宋体; font-size: medium; ">样例说明</span></p><br/>
<p class="MsoNormal"><span style="font-size: medium; "><span lang="EN-US">    </span><span style="font-family: 宋体; ">罗恩最少要修建</span><span lang="EN-US">5</span><span style="font-family: 宋体; ">根柱子（分别在第</span><span lang="EN-US">1</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">5</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">7</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">9</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">13</span><span style="font-family: 宋体; ">个山坡上的点）．钢丝在</span><span lang="EN-US">1-5</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">5-7</span><span style="font-family: 宋体; ">，</span><span lang="EN-US">7-9</span><span style="font-family: 宋体; ">以及</span><span lang="EN-US">12 - 13</span><span style="font-family: 宋体; ">这</span><span lang="EN-US">4</span><span style="font-family: 宋体; ">段上与地面相切．</span></span></p><br/>
<div><span style="font-size: medium; "><span style="font-family: 宋体; "><br/><br/>
</span></span></div><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

