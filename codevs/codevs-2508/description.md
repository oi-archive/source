<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>According to Wikipedia, a printed circuit board, or PCB, is used to mechanically support and electrically <br>connect electronic components using conductive pathways etched from copper sheets laminated onto a non-<br>conductive substrate. Your company wants to produce a new electronic device that will be manufactured <br>using a PCB. The design of the required PCB is partially ready, and has the shape of a closed polygon. It <br>consists of N nodes numbered from 1 to N. Node u and node u+1 are connected by a straight line wire <br>segment and node N is connected to node 1 by a straight line wire segment. Wire segments are non-crossing, <br>that is for any pair of wire segments if they share a common point then this point must be an endpoint of <br>both segments, and each node is the endpoint of exactly two segments. The location of each node is given by <br>x- and y-coordinates, and the origin (0,0) is the lower left corner of the board.</p>
<p>Task <br>You are to write a program that computes all nodes of the circuit that can be connected to the origin by a <br>straight line wire segment that has no common point with the polygon other than the node itself.</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The first line of the input contains one integer, N (1 ≤ N ≤ 100 000) the number of nodes of the circuit.<br>Each of the next N lines contain two integers, x, y (0 &lt; x, y ≤ 1 000 000) the x- and y-coordinates of a node.<br>Nodes are numbered from 1 to N, the input line i+1 contains the coordinates of node i.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>The first line of the output contains one integer M, the number of nodes that can be connected to the <br />origin by a straight line wire segment so that this point is the only common point with any wire segment of <br />the circuit. The second line contains these nodes separated by space in increasing order.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>11<br>7 6<br>4 4<br>3 2<br>1 3<br>9 9<br>13 4<br>8 1<br>6 4<br>9 5<br>8 3<br>11 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3<br>3 4 7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>In 10% of the test cases N does not exceed 1000.<br>If only the first line of the output is correct then 40% of the points are awarded.</p>
</div>
</div>