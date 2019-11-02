<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Colonel Trapp is trapped! For several days he has been ﬁghting General Position on a plateau and his mobile command unit is now stuck at (0, 0), on the edge of a cliff. But the winds are changing! The Colonel has a secret weapon up his sleeve: the &amp;ldquo;epsilon net.&amp;rdquo; Your job, as the Colonel&amp;rsquo;s chief optimization ofﬁcer, is to determine the maximum advantage that a net can yield.<br></p><p>上校陷入了困境！几天以来他一直在高原上战斗并且它的移动指挥单位现在停留在将军位置（0，<span>0），悬崖边上。但是风是在变的！上校有一个秘密武器在他的袖子上：E网（希腊字母epsilon）。作为上校的最优方案工作员，你的工作，就是确定最优的网，使敌人投降。</span></p><p>The epsilon net is a device that looks like a parachute, which you can launch to cover any convex shape. (A shape is convex when, for every pair p,q of points it contains, it also contains the entire line segment pq.) The net shape must include the launch point (0,0).</p><p>E网是一个像降落伞的装置，你可以把它弄成任何凸多边形。</p><p><br>The General has P enemy units stationed at ﬁxed positions and the Colonel has T friendly units. The advantage of a particular net shape equals the number of enemy units it covers, minus the number of friendly units it covers. The General is not a unit.</p><p>这个高地有P个敌人单位驻扎在固定的地点，上校有T个友军单位。最好的网的形状应该使得它能覆盖的敌人单位数减去自己人单位数的值最大。将军不是个单位。</p><p><br>You can assume that &amp;bull; no three points (Trapp&amp;rsquo;s position (0,0), enemy units, and friendly units) lie on a line, &amp;bull; every two points have distinct x-coordinates and y-coordinates, &amp;bull; all co-ordinates (x,y) of the units have y &gt; 0, &amp;bull; all co-ordinates are integers with absolute value at most 1000000000, and &amp;bull; the total number P + T of units is between 1 and 100.</p><p>你可以假设没有三个点在同一线上，每两个点有明确的横纵坐标，所有单位纵坐标大于0，所有坐标都是整数绝对值最大1000000000，并且单位总数在1到100之间。</p>

<img src="/source/codevs/codevs-1273/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xMjczL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTM2MDQ5MzMyNy4wMzAuMjQ5Mjk5MDM2MzY5LnBuZw==.png" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>The ﬁrst line contains P and then T, separated by spaces. Subsequently there are P lines of the form xy giving the enemy units&amp;rsquo; co-ordinates, and then T lines giving the friendly units&amp;rsquo; co- ordinates.</p><p>输入会是P，T。然后P行敌人坐标，T行友军坐标</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>Output a single line with the maximum possible advantage.</p><p>输入仅一行，表示最优解。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 3</p><p>-8 4</p><p>-7 11</p><p> 4 10</p><p> 10 5</p><p> 8 2</p><p> -5 7</p><p> -4 3</p><p> 5 6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>None</p>
</div>
</div>