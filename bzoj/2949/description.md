
# Description

<div class="content"><div><span style="font-size: medium">       蚂蚁和蚜虫是共生的。蚜虫分泌出蜜汁给蚂蚁引用。蚂蚁帮助蚜虫赶走它的天敌——瓢虫。在蚂蚁山附近有一个树，这里是蚜虫生活的地方。蚜虫吸取树的汁液。有n个蚂蚁兵，用1到n编号。一个瓢虫威胁着这个文明，它经常出现在蚜虫活动的地方。当瓢虫坐在树上时，蚂蚁兵会出动把它赶走。他们按照如下的规则：       </span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>树上的任意两点之间都只有一条路径,所有的蚂蚁都沿着它所在点到瓢虫的路径前进，每移动一个位置，花的时间是单位1。</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>如果蚂蚁和瓢虫在同一个位置，那么蚂蚁立即把它赶走。</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>如果某个蚂蚁的路径上有另外一只蚂蚁，那么距离目标较远的蚂蚁待在原地不动，较近的那个蚂蚁继续前进。</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>如果有多个蚂蚁要进入同一个位置，那么选择编号最小的蚂蚁，其余的蚂蚁留在原位置不动。</span></div>
<div style="margin: 0cm 0cm 0pt 42pt; text-indent: -21pt"><span style="font-size: medium">l<span style="font: 7pt &#39;Times New Roman&#39;">         </span>当蚂蚁到达了瓢虫的位置以后，把它赶走，然后停留在该位置。</span></div>
<div><span style="font-size: medium"> </span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">瓢虫是非常顽固的动物，它被赶走了以后还会再停留到别的位置。然后蚂蚁继续行动。为了使问题简单化，我们假定从一个位置到达与它相邻的位置花1个单位的时间。</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">任务：</span></div>
<div><span style="font-size: medium">       读入树的描述，蚂蚁的开始位置，以及瓢虫停留地点。</span></div>
<div><span style="font-size: medium">       给出每个蚂蚁的最后的位置，以及该蚂蚁赶走瓢虫的次数。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行，一个整数n，1&lt;=<i>n</i>&lt;=5000。表示地点的编号。接下来n-1行描述了树里的边，每行两个整数a和b，表示这两点之间相连。然后一行是整数k，1&lt;=<i>k</i>&lt;=1000 and <i>k</i>&lt;=<i>n</i>。是蚂蚁兵的数目。接下来k行，每行一个整数，表示蚂蚁兵开始的位置。没有两个蚂蚁位于一个位置。然后是一个整数<i>l</i>, 1&lt;=<i>l</i>&lt;=500,即瓢虫停留l次。下面的l行每行一个整数，表示瓢虫依次停留的位置。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Output

<div class="content"><div><span style="font-size: medium">       k行。每行两个整数，分别表示第k个蚂蚁最后的位置以及它赶走瓢虫的次数。</span></div></div>

# Sample Input

<div class="content"><span class="sampledata">4<br/>
1 2<br/>
1 3<br/>
2 4<br/>
2<br/>
1<br/>
2<br/>
2<br/>
2<br/>
4<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 0<br/>
4 2<br/>
</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

