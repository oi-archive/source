
# Description

<div class="content"><div style="text-indent: 21pt"><span style="font-size: medium">Farmer John&#39;s farm is made up of an N x N grid of pastures, where each pasture contains one of two different types of grass. To specify these two types of grass, we use the characters ( and ), so for example FJ&#39;s farm might look like the following grid: </span></div>
<div><span style="font-size: medium">(())</span></div>
<div><span style="font-size: medium">)()(</span></div>
<div><span style="font-size: medium">)(((</span></div>
<div><span style="font-size: medium">))))</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">When Bessie the cow travels around the farm, it takes her A units of time to move from a pasture to an adjacent pasture (one step north, south, east, or west) with the same grass type, or B units of time to move to an adjacent pasture with a different grass type. Whenever Bessie travels from one pasture to a distant pasture, she always uses a sequence of steps that takes the minimum amount of time. Please compute the greatest amount of time Bessie will ever need to take while traveling between some pair of pastures on the farm.</span></div>
<div><span style="font-size: medium"> </span></div>
<div><span style="font-size: medium">问题描述</span></div>
<div style="text-indent: 21pt"><span style="font-size: medium">给定一个<i>n</i>×<i>n</i>的一个网格，每个格子有一个字符，要么是’(‘，要么是’)’。每个格子和它的上下左右的四个格子相邻，对于相邻的两个格子<i>x</i>和<i>y</i>，从<i>x</i>走到<i>y</i>的过程中，如果<i>x</i>和<i>y</i>中的字符相同，消耗<i>A</i>单位时间，如果<i>x</i>和<i>y</i>中字符不同，消耗<i>B</i>单位时间。定义点<i>S</i>到点<i>T</i>的时间为<i>D</i>(<i>S</i>,<i>T</i>)，现在想请你求出网格中最大的<i>D</i>(<i>S</i>,<i>T</i>)。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Input

<div class="content"><div><span style="font-size: medium">第一行三个整数<i>n</i>，<i>A</i>，<i>B</i>；</span></div>
<div><span style="font-size: medium">接下来<i>n</i>行描述这个<i>n</i>×<i>n</i>的网格。</span></div>
<div>1 &lt;= n &lt;= 30，1 &lt;= A &lt;= 1,000,000，1 &lt;= B &lt;= 1,000,000。</div></div>

# Output

<div class="content"><div> </div>
<div><span style="font-size: medium"> 一个整数，最大的<i>D</i>(<i>S</i>,<i>T</i>)。</span></div>
<div><span style="font-size: medium"> </span></div></div>

# Sample Input

<div class="content"><span class="sampledata">3 1 2<br/>
(((<br/>
()(<br/>
(()</span></div>

# Sample Output

<div class="content"><span class="sampledata">5<br/>
 样例说明<br/>
左上角到右下角所需的时间为5，是最大值</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver">Silver</a></p></div>

