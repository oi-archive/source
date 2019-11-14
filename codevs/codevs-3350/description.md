<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>众所周知，XX路是连接A村和B村的必经之路。但是这条路上有很多强盗团伙进行犯罪活动。</p>
<p>第i伙强盗控制了Ai到Bi这个路段。根据曾经的规则，不存在I，J，使得Ai&lt;=Aj，Bj&lt;=Bi。但是因为时间的推移，有些强盗的抢劫之地交错了，所以路上还是经常发生争斗。    作为A村的老大史某看不下去，决定重新制定新的规则，新的规则规定：不会有任何两个强盗的地盘有重合，且新的活动地区是老地区的一部分，并且所有强盗团伙的活动范围长度相等。</p>
<p>现在你的任务是去寻找这个最长的可能的区域长度。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个N（1&lt;=N&lt;=100000），代表了强盗团伙的个数，下面N行，每行Ai和Bi代表了当前流氓控制的路段（1&lt;=Ai&lt;Bi&lt;=1000000），保证有解。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一行最长的长度，用最简分数p/q的形式表示。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p>
<p>2 6</p>
<p>1 4</p>
<p>8 12</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5/2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>第一伙强盗掌控的区域为[3.5,6],长度为5/2=2.5。</p>
<p>第二伙强盗掌控的区域为[1,3.5],长度为5/2=2.5。</p>
<p>第三伙强盗掌控的区域为[8,10.5],长度为5/2=2.5。</p>
<p> </p>
<p>40%数据中，N&lt;=100。</p>
<p>即使答案为整数依然输出“p/1”的形式。</p>
</div>
</div>