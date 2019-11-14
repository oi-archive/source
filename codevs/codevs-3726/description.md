<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><span style="">  新机房的软件已经装好了，现在的工作就是测试了，不过在测试的时候，老师发现有些同学正在</span><span style="">玩游戏</span><span style="">(sc..)</span><span style="">，就决定远程把这些玩游戏的学生的机器关机。不过还是网线的问题，到每个学</span><span style="">生机的时间不同，甚至有些学生机是通过其他的学生机连接到教师机上的。关机需要一定的时间，</span><span style="">现在要尽快把这些玩游戏的机器关掉。（教师机为</span><span style="">1</span><span style="">号机）。</span></p><p><span style=""> </span></p><p><span style="">不过</span><span style="">,</span><span style="">有些学生很聪明</span><span style="">,</span><span style="">他们知道老师会把他们远程关机</span><span style="">,</span><span style="">所以</span><span style="">,</span><span style="">有些人可能会把局域网断掉。</span> </p><p><span style="">请你写一个程序，判断这台计算机只否在局域网内。算出最快关闭这几台计算机最短需要多长时</span><span style="">间。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p><span style="">第一行</span> <span style="">两个整数</span><span style="">m,n m</span><span style="">代表机器数</span><span style="">(m&lt;=1000)</span><span style="">，</span><span style="">n</span><span style="">代表相连机器状态的个数</span><span style="">(n&lt;=2000)</span><span style="">。</span> </p><p><span style="">第</span><span style="">2~n+1</span><span style="">行</span><span style=""> x,y,z</span><span style="">，表示</span><span style="">x</span><span style="">和</span><span style="">y</span><span style="">机器之间数据传输需要</span><span style="">z</span><span style="">单位时间。</span><span style="">(1&lt;=x,y&lt;=m,z&lt;=100) </span></p><p><span style="">          </span><span style="">x,y</span><span style="">之间数据传输可以有多个时间</span></p><p><span style="">第</span><span style="">n+2</span><span style="">行：</span><span style="">N </span><span style="">代表要关闭的机器数。</span><span style="">(N&lt;=m) </span></p><p><span style="">接下来</span><span style="">N</span><span style="">个数，表示要关闭的机器。</span> </p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p><span style="font-size:13px;font-family: ÐÂËÎÌå">N</span><span style="font-size:13px;font-family:新宋体">行：每行是第</span><span style="font-size:13px;font-family:ÐÂËÎÌå">i</span><span style="font-size:13px;font-family:新宋体">台机器关闭需要的时间。如果机器不在局域网内，输出</span><span style="font-size:13px;font-family:ÐÂËÎÌå">-1</span><span style="font-size:13px;font-family:新宋体">。</span> </p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p><span style="">5 5 </span></p><p><span style="">1 2 20 </span></p><p><span style="">2 3 30 </span></p><p><span style="">3 4 20 </span></p><p><span style="">4 5 20 </span></p><p><span style="">1 5 100 </span></p><p><span style="">1 </span></p><p><span style="">5 </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p><span style="">90 </span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>详情请见输入描述QWQ</p>
</div>
</div>