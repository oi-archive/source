<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>PP 特别喜欢玩即时战略类游戏，但他觉得那些游戏都有美中不足的地方。灾害总不降临道路，而只降临城市，而且道路不能被占领，没有保护粮草的真实性。于是他就研发了《新三国争霸》。<br> 在这款游戏中，加入灾害对道路的影响（也就是一旦道路W[i，j]受到了灾害的影响，那么在一定时间内，这条路将不能通过）和道路的占领权（对于一条道路W[i，j]，至少需要K[i，j]个士兵才能守住）。<br> PP可真是高手，不一会，就攻下了N-1座城市，加上原来的就有N座城市了，但他忽略了一点……那就是防守同样重要，不过现在还来的及。因为才打完仗所以很多城市都需要建设，PP估算了一下，大概需要T天。他现在无暇分身进攻了，只好在这T天内好好的搞建设了。所以他秒要派士兵占领一些道路，以确保任何两个城市之间都有路（不然敌人就要分而攻之了，是很危险的）。士兵可不是白干活的，每个士兵每天都要吃掉V的军粮。因为有灾害，所以方案可能有变化（每改变一次就需要K的军粮，初始方案也需要K的军粮）。<br> 因为游戏是PP编的，所以他知道什么时候有灾害。PP可是一个很节约的人，他希望这T天在道路的防守上花最少的军粮。<br> N&lt;=300，M&lt;=5000 ，T&lt;=50；</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行有5个整数N，M，T，V，K。N表示有城市数，M表示道路数，T表示需要修养的天数，V表示每个士兵每天吃掉的军粮数，K表示修改一次花掉的军粮数。<br> 以下M行，每行3个数A，B，C。表示A与B有一条路（路是双向的）需要C个士兵才能守住。<br> 第M+2行是一个数P，表示有P个灾害。<br> 以下P行，每行4个数，X，Y，T1，T2。表示X到Y的这条路，在T1到T2这几天都会受灾害。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>T天在道路的防守上花费最少的军粮。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 5 10 30<br>1 2 1<br>2 3 2<br>1 3 4<br>1<br>1 3 2 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>180</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>各个测试点1s</p>
</div>
</div>