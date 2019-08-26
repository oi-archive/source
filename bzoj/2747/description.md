
# Description

<div class="content"><p><span style="font-size: medium">小H是一位探险家。在险峻的珠穆朗玛峰，原始辽阔的非洲大草原，美丽冻人的南极大陆等 地方都留下过这位探险家的足迹。这次，他来到了位于南美洲充斥着大量毒虫猛兽的以及各 式各样传说的亚马逊热带雨林进行探险。为此，他花了许多时间来准备这次激动人心的探险。 在准备就绪后，小H和他的助手在当地导游的带领下踏入了这片雨林。 通过GPS定位系统，他们获得了雨林大致的地图。这个地图是一个n行m列的字符网格 图，’.’表示的是空地，’*’表示的是不可通行的区域，’#’表示的是需要清理的区 域，’H’表示小H所在的位置，该区域是空地。他们的移动方式有t种，用 a[i],b[i](1&lt;=i&lt;=t)表示，假设他们所在的位置为第x行第y列，那么他们下一步的位置将 是第x+a[i]行第y+b[i]列，也可以是反方向，即第x-a[i]行第y-b[i]列。小H一行人每天 可在选择一种移动方式，朝着正方向或者反方向连续走若干步之后停下，不可以不走。在当 天的行走过程中，他们不可以到达不可通行的区域，如果他们到达了一个需要清理的区域， 他们会停止移动。为了以后探险的方便，他们会用该天剩下的时间来清理该区域，之后该区 域将永久变成空地。 现在，为了使探险活动顺利的进行，他们将q个询问通过网络发送给了你，询问他们在 第d[i](1&lt;=i&lt;=q)天能到达的区域个数，题目保证不会有无路可走的情况。你能帮助他解决 这个问题吗？ <br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">输入的第1行包含三个正整数，分别表示n、m、t。  <br/>
在第2行至第n+1行中，每行都有m个字符（只可能是’.’，’*’，’#’，’H’，其中’H’ 有且只有一个）。 <br/>
在第n+2行至第n+t+1行中，每行有两个整数，分别表示a[i]，b[i]（a[i]，b[i]不可能 同时为0）。 <br/>
在第n+t+2行包含一个正整数，表示q。 <br/>
在第n+t+3行至第n+t+q+2行共有q个整数，表示他们所询问的时间点（即d[i]）。 <br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font size="4">输出共q行，对于每一个询问，输出他们所能走到的地点的个数。 <br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata"><br/>
3  3 2<br/>
H#. *.. <br/>
… <br/>
1  0<br/>
0  1<br/>
2 <br/>
 1 2 <br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">1 <br/>
4 <br/>
 <br/>
 <br/>
 </span></div>

# Hint

<div class="content"><p></p><p><br/><br/>
【数据范围】 <br/><br/>
对于20%的数据，满足n，m&lt;=4, q &lt;= 100； <br/><br/>
对于70%的数据，满足n，m&lt;=300； <br/><br/>
对于100%的数据，满足n，m&lt;=1000, t&lt;=5, q&lt;=1000, 0&lt;=d[i]&lt;=10^9；</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

