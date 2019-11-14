
# Description

<div class="content"><p><span style="font-size: medium">　　某校开展了同学们喜闻乐见的阳光长跑活动。为了能“为祖国健康工作五十年”，同学们纷纷离开寝室，离开教室，离开实验室，到操场参加3000米长跑运动。一时间操场上熙熙攘攘，摩肩接踵，盛况空前。<br/>
　　为了让同学们更好地监督自己，学校推行了刷卡机制。<br/>
　　学校中有n个地点，用1到n的整数表示，每个地点设有若干个刷卡机。<br/>
　　有以下三类事件：<br/>
　　1、修建了一条连接A地点和B地点的跑道。<br/>
　　2、A点的刷卡机台数变为了B。<br/>
　　3、进行了一次长跑。问一个同学从A出发，最后到达B最多可以刷卡多少次。具体的要求如下：<br/>
　　当同学到达一个地点时，他可以在这里的每一台刷卡机上都刷卡。但每台刷卡机只能刷卡一次，即使多次到达同一地点也不能多次刷卡。<br/>
　　为了安全起见，每条跑道都需要设定一个方向，这条跑道只能按照这个方向单向通行。最多的刷卡次数即为在任意设定跑道方向，按照任意路径从A地点到B地点能刷卡的最多次数。<br/>
</span></p></div>

# Input

<div class="content"><p><font size="4">　　输入的第一行包含两个正整数n,m，表示地点的个数和操作的个数。<br/>
　　第二行包含n个非负整数，其中第i个数为第个地点最开始刷卡机的台数。<br/>
　　接下来有m行，每行包含三个非负整数P,A,B，P为事件类型，A,B为事件的两个参数。<br/>
　　最初所有地点之间都没有跑道。<br/>
　　每行相邻的两个数之间均用一个空格隔开。表示地点编号的数均在1到n之间，每个地点的刷卡机台数始终不超过10000，P=1,2,3。<br/>
</font></p></div>

# Output

<div class="content"><p><br/>
<font size="4">　　输出的行数等于第3类事件的个数，每行表示一个第3类事件。如果该情况下存在一种设定跑道方向的方案和路径的方案，可以到达，则输出最多可以刷卡的次数。如果A不能到达B，则输出-1。<br/>
</font></p></div>

# Sample Input

<div class="content"><span class="sampledata">9 31<br/>
10 20 30 40 50 60 70 80 90<br/>
3 1 2<br/>
1 1 3<br/>
1 1 2<br/>
1 8 9<br/>
1 2 4<br/>
1 2 5<br/>
1 4 6<br/>
1 4 7<br/>
3 1 8<br/>
3 8 8<br/>
1 8 9<br/>
3 8 8<br/>
3 7 5<br/>
3 7 3<br/>
1 4 1<br/>
3 7 5<br/>
3 7 3<br/>
1 5 7<br/>
3 6 5<br/>
3 3 6<br/>
1 2 4<br/>
1 5 5<br/>
3 3 6<br/>
2 8 180<br/>
3 8 8<br/>
2 9 190<br/>
3 9 9<br/>
2 5 150<br/>
3 3 6<br/>
2 1 210<br/>
3 3 6<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata"><br/>
-1<br/>
-1<br/>
80<br/>
170<br/>
180<br/>
170<br/>
190<br/>
170<br/>
250<br/>
280<br/>
280<br/>
270<br/>
370<br/>
380<br/>
580<br/>
</span></div>

# Hint

<div class="content"><p></p><p>数据规模及约定<br/><br/>
　　对于100%的数据，m&lt;=5n，任意时刻，每个地点的刷卡机台数不超过10000。N&lt;=<span style="display: inline! important; float: none; word-spacing: 0px; font: 14px &#39;Times New Roman&#39;, ����; text-transform: none; color: rgb(32,0,0); text-indent: 0px; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px">1.5×10</span><sup style="font-weight: normal; word-spacing: 0px; text-transform: none; color: rgb(32,0,0); text-indent: 0px; line-height: normal; font-style: normal; font-family: &#39;Times New Roman&#39;, ����; white-space: normal; letter-spacing: normal; background-color: rgb(255,255,255); font-variant: normal; orphans: 2; widows: 2; webkit-text-size-adjust: auto; webkit-text-stroke-width: 0px">5</sup></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=中国国家队清华集训 2012-2013 第二天
">中国国家队清华集训 2012-2013 第二天<br/>
</a></p></div>

