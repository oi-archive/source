
# Description

<div class="content"><div>最近比特镇正在迅速建成。沿着美丽的大街，一座座新建筑拔地而起。小Q喜欢沿着大街走，但问题是不同的建筑位于街对面。为了从一个建筑到另一个建筑，有时需要通过漫长的步行穿过最近的人行道。所以他决定写一个程序，计算如何沿着大街平移所有人行道，使得人行道的布局最有利于行人。他希望尽可能多的人行道出现在某些建筑物的前面，同时人行道的移动距离应当是最小的。</div>
<div>大街以直线表示，人行道被视为这条线上的点。所有建筑物都平行于大街，所以你可以认为它们是直线上的一条条线段。每条线段都具有左边界和右边界。如果某人行道位于某建筑物的左右边界之间（包括边界点），则你可以认为该人行道位于该建筑物的前方。由于人行道已经按照某些标准建立，小Q决定保持它们之间的距离，所以他想将所有的人行道移动相同的距离。</div>
<div>请帮助小Q写一个程序计算最优布局</div></div>

# Input

<div class="content"><div>第一行包含两个正整数n,m(1&lt;=n&lt;=10000,1&lt;=m&lt;=1000)，分别表示人行道和建筑的个数。</div>
<div>第二行包含n个整数a_i(0&lt;=a_i&lt;=10^6)，分别表示每条人行道的坐标，可能存在两条人行道重合。</div>
<div>接下来m行，每行两个整数l_i,r_i(0&lt;=l_i&lt;r_i&lt;=10^6)，分别表示每座建筑的左右边界，这些线段可以相互重叠。</div></div>

# Output

<div class="content"><div>输出一行两个整数d和s，其中d表示平移距离的绝对值，s表示出现在至少一座建筑物前面的人行道个数。你需要输出s最大的解，若有多个d使得s最大，那么输出d最小的解。注意你可以向左或者向右平移人行道。</div></div>

# Sample Input

<div class="content"><span class="sampledata">4 2<br/>
1 6 6 1<br/>
4 5<br/>
3 5</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=本OJ付费获取">本OJ付费获取</a></p></div>

