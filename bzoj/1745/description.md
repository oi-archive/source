
# Description

<div class="content"><p><span style="font-size: medium">Figuring that they cannot do worse than the humans have, Farmer John&#39;s cows have decided to start an airline. Being cows, they decide to cater to the heretofore-untapped market of cows as passengers. They plan to serve the cows who live along the western coast of Lake Michigan. Each morning, they will fly from the northern-most point of the coast southward towards Chicowgo, making many stops along the way. Each evening, they will fly back north to the northern-most point. They need your help to decide which passengers to carry each day. Each of N (1 &lt;= N &lt;= 10,000) farms numbered 1..N along the coast contains an airport (Farm 1 is northern-most; farm N is southern-most). On this day, K (1 &lt;= K &lt;= 50,000) groups of cows wish to travel. Each group of cows wants to fly from a particular farm to another particular farm. The airline, if it wishes, is allowed to stop and pick up only part of a group. Cows that start a flight, however, must stay on the plane until they reach their destination. Given the capacity C (1 &lt;= C &lt;= 100) of the airplane and the groups of cows that want to travel, determine the maximum number of cows that the airline can fly to their destination. </span></p>
<div><span style="font-size: medium">    为了表示不能输给人类，农场的奶牛们决定成立一家航空公司．她们计划每天早晨，从密歇根湖湖岸的最北端飞向最南端，晚上从最南端飞往最北端．在旅途中，航空公司可以安排飞机停在某些机场．他们需要你帮助来决定每天携带哪些旅客．沿着湖岸，有N(1≤N≤10000)个由北至南编号为1到N的农场．每个农场都有一个机场．这天，有k(l≤七≤50000)群牛想要乘坐飞机旅行．每一群牛想要从一个农场飞往另一个农场．航班可以在某些农场停下带上部分或全体的牛．奶牛们登机后会一直停留直至达到目的地    提供给你飞机的容量C(1≤C≤100)，同时提供给你想要旅行的奶牛的信息，请你计算出这一天的航班最多能够满足几只奶牛的愿望．</span></div></div>

# Input

<div class="content"><p><span style="font-size: medium">* Line 1: Three space-separated integers: K, N, and C * Lines 2..K+1: Each line contains three space-separated integers S, E, and M that specify a group of cows that wishes to travel. The M (1 &lt;= M &lt;= C) cows are currently at farm S and want to travel to farm E (S != E). </span></p>
<div><span style="font-size: medium">    第1行：3个用空格隔开的整数K，N和C.</span></div>
<div><span style="font-size: medium">    第2到K+1行：每一行有3个用空格隔开的整数S，E，M.表示有M只奶牛想从农场S乘飞机到农场E．</span></div></div>

# Output

<div class="content"><p><span style="font-size: medium">* Line 1: The maximum number of cows that can be flown to their destination. This is the sum of the number of cows flown to their destination on the flight southward in the morning plus the number of cows flown to their destination on the flight northward in the evening. </span></p>
<div><span style="font-size: medium">    可以完成旅行的奶牛人数的最大值．</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4 8 3<br/>
1 3 2<br/>
2 8 3<br/>
4 7 1<br/>
8 3 2<br/>
<br/>
INPUT DETAILS:<br/>
<br/>
Four groups of cows, eight farms, and three seats on the<br/>
plane.<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">6<br/>
</span></div>

# Hint

<div class="content"><p></p><p class="MsoNormal" style="margin: 0cm 0cm 0pt"><span style="font-size: medium"><span lang="EN-US"><font face="Times New Roman">  3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">群想要旅行的奶牛，</span><span lang="EN-US"><font face="Times New Roman">8</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个农场，飞机上有</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">个座位．早晨，飞机把</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">只牛从</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">带到</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">只牛</span></span><span style="font-size: medium"><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">从</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">带到</span><span lang="EN-US"><font face="Times New Roman">8</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">，</span><span lang="EN-US"><font face="Times New Roman">1</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">只牛从</span><span lang="EN-US"><font face="Times New Roman">4</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">带到</span><span lang="EN-US"><font face="Times New Roman">7</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">．晚上，航班把</span><span lang="EN-US"><font face="Times New Roman">2</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">尺牛从</span><span lang="EN-US"><font face="Times New Roman">8</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">带到</span><span lang="EN-US"><font face="Times New Roman">3</font></span><span style="font-family: 宋体; mso-ascii-font-family: &#39;Times New Roman&#39;; mso-hansi-font-family: &#39;Times New Roman&#39;">．</span></span></p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

