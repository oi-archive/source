
# Description

<div class="content"><p>Farmer John has recently built an enormous barn consisting of an N×NN×N grid of rooms (2≤N≤100), numbered from (1,1)up to (N,N). Being somewhat afraid of the dark, Bessie the cow wants to turn on the lights in as many rooms as possible.<br/>
<br/>
Bessie starts in room (1,1), the only room that is initially lit. In some rooms, she will find light switches that she can use to toggle the lights in other rooms; for example there might be a switch in room (1,1) that toggles the lights in room (1,2)(1,2). Bessie can only travel through lit rooms, and she can only move from a room (x,y)(x,y) to its four adjacent neighbors (x−1,y), (x+1,y), (x,y−1)(x,y−1) and (x,y+1) (or possibly fewer neighbors if this room is on the boundary of the grid).<br/>
<br/>
Please determine the maximum number of rooms Bessie can illuminate.</p>
<p></p>
<p>有N*N个房间，组成了一张N*N的网格图，Bessie一开始位于左上角(1,1)，并且只能上下左右行走。</p>
<p>一开始，只有(1,1)这个房间的灯是亮着的，Bessie只能在亮着灯的房间里活动。</p>
<p>有另外M条信息，每条信息包含四个数a,b,c,d，表示房间(a,b)里有房间(c,d)的灯的开关。</p>
<p>请计算出最多有多少个房间的灯可以被打开</p>
<p></p></div>

# Input

<div class="content"><p>The first line of input contains integers NN and MM (1≤M≤20,000).<br/>
<br/>
The  next MM lines each describe a single light switch with four integers  xx, yy, aa, bb, that a switch in room (x,y) can be used to toggle the  lights in room (a,b). Multiple switches may exist in any room, and  multiple switches may toggle the lights of any room.</p></div>

# Output

<div class="content"><p>A single line giving the maximum number of rooms Bessie can illuminate.</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 6<br/>
1 1 1 2<br/>
2 1 2 2<br/>
1 1 1 3<br/>
2 3 3 1<br/>
1 3 1 2<br/>
1 3 2 1</span></div>

# Sample Output

<div class="content"><span class="sampledata">5</span></div>

# Hint

<div class="content"><p></p><p>Here, Bessie can use the switch in (1,1) to turn on lights in (1,2) and (1,3). She can then walk to (1,3) and turn on the lights in (2,1), from which she can turn on the lights in (2,2). The switch in (2,3) is inaccessible to her, being in an unlit room. She can therefore illuminate at most 5 rooms.</p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Silver鸣谢Claris提供译文">Silver鸣谢Claris提供译文</a></p></div>

