<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span>　　某校开展了同学们喜闻乐见的阳光长跑活动。为了能“为祖国健康工作五十年”，同学们纷纷离开寝室，离开教室，离开实验室，到操场参加3000米长跑运动。一时间操场上熙熙攘攘，摩肩接踵，盛况空前。</span><br><span>　　为了让同学们更好地监督自己，学校推行了刷卡机制。</span><br><span>　　学校中有n个地点，用1到n的整数表示，每个地点设有若干个刷卡机。</span><br><span>　　有以下三类事件：</span><br><span>　　1、修建了一条连接A地点和B地点的跑道。</span><br><span>　　2、A点的刷卡机台数变为了B。</span><br><span>　　3、进行了一次长跑。问一个同学从A出发，最后到达B最多可以刷卡多少次。具体的要求如下：</span><br><span>　　当同学到达一个地点时，他可以在这里的每一台刷卡机上都刷卡。但每台刷卡机只能刷卡一次，即使多次到达同一地点也不能多次刷卡。</span><br><span>　　为了安全起见，每条跑道都需要设定一个方向，这条跑道只能按照这个方向单向通行。最多的刷卡次数即为在任意设定跑道方向，按照任意路径从A地点到B地点能刷卡的最多次数。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span>　　输入的第一行包含两个正整数n,m，表示地点的个数和操作的个数。</span><br><span>　　第二行包含n个非负整数，其中第i个数为第个地点最开始刷卡机的台数。</span><br><span>　　接下来有m行，每行包含三个非负整数P,A,B，P为事件类型，A,B为事件的两个参数。</span><br><span>　　最初所有地点之间都没有跑道。</span><br><span>　　每行相邻的两个数之间均用一个空格隔开。表示地点编号的数均在1到n之间，每个地点的刷卡机台数始终不超过10000，P=1,2,3。</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span>　　输出的行数等于第3类事件的个数，每行表示一个第3类事件。如果该情况下存在一种设定跑道方向的方案和路径的方案，可以到达，则输出最多可以刷卡的次数。如果A不能到达B，则输出-1。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span>9 31</span><br><span>10 20 30 40 50 60 70 80 90</span><br><span>3 1 2</span><br><span>1 1 3</span><br><span>1 1 2</span><br><span>1 8 9</span><br><span>1 2 4</span><br><span>1 2 5</span><br><span>1 4 6</span><br><span>1 4 7</span><br><span>3 1 8</span><br><span>3 8 8</span><br><span>1 8 9</span><br><span>3 8 8</span><br><span>3 7 5</span><br><span>3 7 3</span><br><span>1 4 1</span><br><span>3 7 5</span><br><span>3 7 3</span><br><span>1 5 7</span><br><span>3 6 5</span><br><span>3 3 6</span><br><span>1 2 4</span><br><span>1 5 5</span><br><span>3 3 6</span><br><span>2 8 180</span><br><span>3 8 8</span><br><span>2 9 190</span><br><span>3 9 9</span><br><span>2 5 150</span><br><span>3 3 6</span><br><span>2 1 210</span><br><span>3 3 6</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span>-1</span><br><span>-1</span><br><span>80</span><br><span>170</span><br><span>180</span><br><span>170</span><br><span>190</span><br><span>170</span><br><span>250</span><br><span>280</span><br><span>280</span><br><span>270</span><br><span>370</span><br><span>380</span><br><span>580</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span>　　对于100%的数据，m&lt;=5n，任意时刻，每个地点的刷卡机台数不超过10000。具体每组数据的规模如下</span></p>
<table cellpadding="2px" cellspacing="0">
<tbody>
<tr>
<td valign="top">编号</td>
<td valign="top">n</td>
<td valign="top">编号</td>
<td valign="top">n</td>
</tr>
<tr>
<td valign="top">1</td>
<td valign="top">10</td>
<td valign="top">6</td>
<td valign="top">5×10<sup>4</sup></td>
</tr>
<tr>
<td valign="top">2</td>
<td valign="top">10<sup>2</sup></td>
<td valign="top">7</td>
<td valign="top">10<sup>5</sup></td>
</tr>
<tr>
<td valign="top">3</td>
<td valign="top">10<sup>3</sup></td>
<td valign="top">8</td>
<td valign="top">10<sup>5</sup></td>
</tr>
<tr>
<td valign="top">4</td>
<td valign="top">10<sup>4</sup></td>
<td valign="top">9</td>
<td valign="top">1.5×10<sup>5</sup></td>
</tr>
<tr>
<td valign="top">5</td>
<td valign="top">2×10<sup>4</sup></td>
<td valign="top">10</td>
<td valign="top">1.5×10<sup>5</sup></td>
</tr>
</tbody>
</table>
<p> </p>
<p>来源：<span>中国国家队清华集训 2012-2013 第二天</span></p>
</div>
</div>