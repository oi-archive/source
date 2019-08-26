
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">铁人双项比赛是吉林教育学院的一项传统体育项目。该项目比赛由长跑和骑自行车组成，参赛选手必须先完成k公里的长跑，然后完成r公里的骑车，才能到达终点。每个参赛选手所擅长的项目不同，有的擅长长跑，有的擅长骑车。如果总赛程s=k+r一定，那么K越大，对擅长长跑的选手越有利；k越小，对擅长骑车的选手越有利。</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium"> </span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">现在给定总赛程s，以及每个选手长跑和骑车的平均速度，请你求出对于某个指定的选手最有利的k和r。所谓最有利，是指选择了这个k和r后，该选手可以获得冠军，且领先第2名尽量地多。</span></div></div>

# Input

<div class="content"><div style="text-indent: 21.75pt"><span style="font-size: medium">你的程序从文件读入输入数据。</span></div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">输入的第一行是两个正整s和n，s表示总赛程（单位为公里，s≤2<sup>31</sup>），n表示参赛总人数（2≤n≤100）。</span></div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">接下来的n行每行是两个实数，分别表示每个选手长跑的平均速度和骑车的平均速度（单位为千米/小时）。</span></div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">第n个选手就是指定的选手，你的任务是求出对他最有利的k和r。</span></div></div>

# Output

<div class="content"><div style="margin: 6pt 0cm; line-height: 18pt"> </div>
<div style="text-indent: 21.75pt"><span style="font-size: medium">你的程序的输出包括三个数k，r, t，分别表示对第n号选手最有利的k和r（浮点数，保留小数点后2位），以及在选择k和r的情况下，第n号选手最多可以领先第2名多少秒（四舍五入到整数）；如果另一个选手和该选手并列第一，则t <sub>i</sub>=0。倘若无论选择什么k，r都不能使第n号选手获胜，则输出“NO”。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">100  3<br/>
10.0  40.0<br/>
20.0  30.0<br/>
15.0  35.0<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">14.29  85.71  612</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

