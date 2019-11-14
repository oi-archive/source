
# Description

<div class="content"><div>位于Ultima Thule的公园内的一条双重观光道路是由以下原理工作：</div>
<div>*我们引入直角坐标系。</div>
<div>*在一些时刻会有2个游客同时从点（-1,0）和（1,0）出发（去散步）。其中第一个人出发点（-1,0）,第二个人出发点为（1,0）。</div>
<div>*每一对游客都以相同的速度1行动（每秒前进单位长度）。第一个人沿直线x=-1、第二个人沿直线x=1行动。他们都向y轴正方向移动。</div>
<div>*在一些时刻墙会出现。墙（li,ri）是一条在点（0,li）和（0,ri）之间的线段。每个墙都瞬间出现。</div>
<div>Ultima Thule官方想要了解对于每一对同时出发的游客，他们将会有多长时间无法彼此望见？2个游客不能看到对方当且仅当他们位置的连线与至少1面墙相交。2条线段相交是指他们至少有1个公共点。我们假定线段的端点属于这条线段。</div>
<div>帮助他们计算所要求的时间。注意墙可以相交（以任何方式）或重合。</div>
<p></p></div>

# Input

<div class="content"><div>第一行包含2个空格隔开的整数n、m（1&lt;=n,m&lt;=10^5）——游客的对数和墙的数目。</div>
<div>接下来m行每行3个空格隔开的整数li，ri，ti（0&lt;=li&lt;ri&lt;=10^9,0&lt;=ti&lt;=10^9）——墙的2端和出现的时间。</div>
<div>最后一行包含n个严格递增、空格隔开的整数q1，q2，…，qn（0&lt;=qi&lt;=10^9）——每对游客出发的时刻。</div>
<p></p></div>

# Output

<div class="content"><div>对每对游客输出一行一个整数——这对游客不能相互看见的时间是几秒。按照读入游客出发时间的顺序输出答案。</div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">Input1:<br/>
2 2<br/>
1 4 3<br/>
3 6 5<br/>
0 1<br/>
Input2:<br/>
3 3<br/>
0 3 4<br/>
0 1 2<br/>
2 4 0<br/>
1 3 4</span></div>

# Sample Output

<div class="content"><span class="sampledata">Output1:<br/>
2<br/>
4<br/>
Output2:<br/>
2<br/>
4<br/>
4</span></div>

# Hint

<div class="content"><p></p><div>1&lt;=n,m&lt;=10^5,0&lt;=li&lt;ri&lt;=10^9,0&lt;=ti&lt;=10^9,0&lt;=qi&lt;=10^9</div><br/>
<div></div><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

