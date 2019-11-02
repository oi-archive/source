<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Google SketchUp is an easy-to-use program that lets you create, modify and share 3D models. In this problem, you're to write a simplified version of SketchUp called My SketchUp. Since 3D is complex, My SketchUp will be in 2D only.</p>
<p>SketchUp is intuitive. To understand this, suppose you've drawn two line segments that intersect other, like this:<img height="96" src="/source/codevs/codevs-2694/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yNjk0L2h0dHA6Ly91dmEub25saW5lanVkZ2Uub3JnL2V4dGVybmFsLzEyMy9wMTIzMDZhLmpwZw==.jpg" width="597"></p>
<p>Then, you click your mouse at the red dot. If you're using AutoCAD, you'll select a whole segment (shown in the middle picture), but in My SketchUp, you'll only select a small segment (shown in the right picture), because the two segment you've drawn cut each other! What's more, if you remove two small segments as shown below, the other two small segments will automatically join up to become one segment again! Note that in the middle picture, you cannot select the "long" segment as a whole, because it's still cut into two pieces.</p>
<p><img height="122" src="/source/codevs/codevs-2694/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yNjk0L2h0dHA6Ly91dmEub25saW5lanVkZ2Uub3JnL2V4dGVybmFsLzEyMy9wMTIzMDZiLmpwZw==.jpg" width="595"></p>
<p>Here is the general rule: segments that intersect each other actually cut each other; and there will be no "redundant" points that can be removed without affecting the appearance of the picture. As a result, the in-memory data structure of the segments can be deduced merely from the appearance. If two pictures look the same, they are the same internally. For example, if you draw (0,0)-(1,0), then (1,0)-(2,0), you'll have only one segment: (0,0)-(2,0), if you draw (0,0)-(1,0) twice, you'll only get one. In the picture below, there are 14 vertices and 15 segments (no matter how you draw this picture!!).</p>
<p><img height="145" src="/source/codevs/codevs-2694/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0yNjk0L2h0dHA6Ly91dmEub25saW5lanVkZ2Uub3JnL2V4dGVybmFsLzEyMy9wMTIzMDZjLmpwZw==.jpg" width="179"></p>
<p>Your task is to execute a sequence of commands (described in the input format section) and print the description of the resulting picture. Vertices are sorted in ascending order of x, then ascending order of y; Segments are represented by a pair of integers a and b (a &lt; b), that means the segment is connecting vertex a and vertex b (vertices are numbered from 1).</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>There will be at most 25 test cases. Each case begins with one integer n (1&lt;=n&lt;=100), the number of operations. Each of the following n lines is formatted as one of:</p>
<pre>DRAW x1 y1 x2 y2 x3 y3...</pre>
<p>or:</p>
<pre>REMOVE x y d</pre>
<p>In the draw operation, you're drawing a poly-line (x1,y1)-(x2,y2)-(x3,y3)-..., note that if the last point equals to the first point, you're actually drawing closed poly-line (but not necessarily a polygon, since the poly-line could be self-intersecting. There will be at least 2 and at most 20 points in a draw operation.</p>
<p>In the remove operation, all the line segments whose distance from (x,y) is at most d, are removed simultaneously (be careful about this!). If no segments satisfy this condition, this operation takes no effect. -1000&lt;=x1,y1,x2,y2&lt;=1000, 0&lt;=d&lt;=10.</p>
<p>There is a special command "END" following the last draw/remove operation. The last test case is followed by a line with n=0, which should not be processed.</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>For each test case, print the number of vertices, followed by the coordinates of the vertices (one vertex per line), sorted as stated in the problem statement. The next line contains the number of segments, followed by the descriptions of the segments.</p>
<p>Tips: In this problem, your output must match the standard output perfectly. In order to prevent you from printing "-0.00" instead of "0.00", you're encouraged to add to small number (e.g. 1e-6) to each number you print.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7</p>
<p>DRAW 10 0 50 0 50 30 10 30 10 0</p>
<p>DRAW 0 10 10 10 10 20 0 20 0 10</p>
<p>DRAW 40 0 40 10 50 10 50 0</p>
<p>REMOVE 45 1 1</p>
<p>DRAW 50 20 20 20 20 30</p>
<p>DRAW 40 20 40 30</p>
<p>REMOVE 42 23 3</p>
<p>END</p>
<p>7</p>
<p>DRAW 0 0 10 0</p>
<p>DRAW 1 0 11 0</p>
<p>DRAW 12 0 15 0</p>
<p>DRAW 5 0 5 1</p>
<p>DRAW 8 0 8 1</p>
<p>REMOVE 5 2 1</p>
<p>DRAW 11 0 12 0</p>
<p>END</p>
<p>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<pre>14
0.00 10.00
0.00 20.00
10.00 0.00
10.00 10.00
10.00 20.00
10.00 30.00
20.00 20.00
20.00 30.00
40.00 0.00
40.00 10.00
40.00 20.00
50.00 0.00
50.00 10.00
50.00 30.00
15
1 2
1 4
2 5
3 4
3 9
4 5
5 6
6 8
7 8
7 11
8 14
9 10
10 13
12 13
13 14
4
0.00 0.00
8.00 0.00
8.00 1.00
15.00 0.00
3
1 2
2 3
2 4
</pre>
<pre> </pre>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><em>Rujia Liu's Present 4: A Contest Dedicated to Geometry and CG Lovers</em></p>
<p><em>Special Thanks: Dun Liang</em></p>
</div>
</div>