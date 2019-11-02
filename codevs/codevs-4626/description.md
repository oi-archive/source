<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">跳跳棋是在一条数轴上进行的。棋子只能摆在整点上。每个点不能摆超过一个棋子。我们用跳跳棋来做一个简单的游戏：棋盘上有3颗棋子，分别在a，b，c这三个位置。我们要通过最少的跳动把他们的位置移动成x，y，z。（棋子是没有区别的）跳动的规则很简单，任意选一颗棋子，对一颗中轴棋子跳动。跳动后两颗棋子距离不变。一次只允许跳过1颗棋子。 </span><img border="0" height="128" src="/source/codevs/codevs-4626/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy00NjI2L2h0dHA6Ly93d3cubHlkc3kuY29tL0p1ZGdlT25saW5lL2ltYWdlcy8yMTQ0LmpwZw==.jpg" style="font-family: arial, verdana, helvetica, sans-serif;" width="384"><span style=""> 写一个程序，首先判断是否可以完成任务。如果可以，输出最少需要的跳动次数。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行包含三个整数，表示当前棋子的位置a b c。（互不相同）第二行包含三个整数，表示目标位置x y z。（互不相同）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<span style="font-family: 微软雅黑, &#39;Microsoft YaHei&#39;;">如果无解，输出一行NO。如果可以到达，第一行输出YES，第二行输出最少步数。</span>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">1 2 3</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">0 3 5</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="font-family: monospace;">YES</span><br style="font-family: arial, verdana, helvetica, sans-serif;"><span style="font-family: monospace;">2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>保证输出结果不超过1e9<br></p>
</div>
</div>