<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>由于XTH提交了一道名为‘WXP的普及之路’的题目，所以现在WXP要杀了他。然而这并没有什么卵用囧，因为WXP年老体衰（WXP：你才年老体衰呢），他在机房放置了许多<span style="">毒气喷射口来</span>追杀XTH（丧心病狂233），作为XTH的一个朋友，请你用电脑看一看他能否逃离</p><p><span style="">机房里面有若干个毒气喷射口，已知毒气的扩散速度是每单位时间向上下左右扩散一格，而</span><span style=""><span style="font-family: Verdana, sans-serif;">XTH</span></span><span style="">的逃逸速度也是每单位时间向上下左右移动一格。所有的毒气喷射口都是同时喷发的，当毒气喷射时，</span><span style=""><span style="font-family: Verdana, sans-serif;">你</span></span><span style="">就马上通知</span><span style=""><span style="font-family: Verdana, sans-serif;">XTH</span></span><span style="">逃离，</span><span style=""><span style="font-family: Verdana, sans-serif;">XTH</span></span><span style="">必须在不遇到毒气的情况下尽快逃离机房。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style=""><span style="">机房地图用矩阵表示，</span><span style="">符号</span><span style="font-family: Verdana, sans-serif;">.</span><span style="">表示通路，符号</span><span style="font-family: Verdana, sans-serif;">X</span><span style="">表示障碍物，符号</span><span style="font-family: Verdana, sans-serif;">E</span><span style="">表示门口，符号</span><span style="font-family: Verdana, sans-serif;">D</span><span style="">表示毒气喷射口所在地，符号</span><span style="font-family: Verdana, sans-serif;">P</span><span style="">表示</span><span style=""><span style="font-family: Verdana, sans-serif;">XTH</span></span><span style="">当前的位置。</span></span></p><p style=""><span style="">输入首先是两个整数</span><span style="font-family: Verdana, sans-serif;">m,n(2&lt;=m,n&lt;=1000)</span><span style="">表示矩阵的大小。接下来是</span><span style="font-family: Verdana, sans-serif;">m</span><span style="">行</span><span style="font-family: Verdana, sans-serif;">n</span><span style="">列的矩阵图。矩阵描述之外的地方都是障碍物且只有一个逃离的门口，但可能有多个毒气喷射口，且扩散到门口的毒气立即消散。输入有多组数据，当</span><span style="font-family: Verdana, sans-serif;">m,n</span><span style="">是</span><span style="font-family: Verdana, sans-serif;">0 0</span><span style="">时表示输入结束。</span></p><p><span style=""><span style=""></span></span><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="margin-top:10px;margin-right:0;margin-bottom:10px;margin-left: 0;line-height:23px;background:white"><span style="font-size: 15px;font-family: 宋体;color: rgb(51, 51, 51)">如果</span><span style="font-size: 15px; color: rgb(51, 51, 51);"><span style="font-family:Verdana, sans-serif">XTH</span></span><span style="font-size: 15px;font-family: 宋体;color: rgb(51, 51, 51)">能够顺利逃离机房，则输出最快逃离机房的时间，否则输出</span><span style="font-size: 15px;font-family: Verdana, sans-serif;color: rgb(51, 51, 51)">“XTH is extremely dangerous!”</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>5 10</pre><pre>XXXXX..XXX</pre><pre>XXXE...XXX</pre><pre>XX.......X</pre><pre>X......P.X</pre><pre>XD.....XXX</pre><pre>5 10</pre><pre>XXXXX..XXX</pre><pre>XXXE...XXX</pre><pre>XX.......X</pre><pre>X......P.X</pre><pre>X.D....XXX</pre><pre>0 0</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>6</pre><pre>XTH is extremely dangerous!</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>RT<br></p>
</div>
</div>