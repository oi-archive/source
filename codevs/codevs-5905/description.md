<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>在YouSiki的童年记忆里，自己256M内存的笔记本玩不了红警、Dota，所以只能靠《是男人就下一百层》这个无聊游戏打发时间。</p><p>有一天晚上，YouSiki梦见自己进入了这个可怕的游戏中，摆在他面前的是N个好板子（踩上就会恢复一点体力），以及M个坏板子（踩上就会失去一点体力）。</p><p><span style="text-decoration: line-through;">最无聊的是，那些跳跳板、履带板、翻面板都被出题人吃掉了。</span></p><p>值得一提的是，在这个游戏中，初始的体力为0，中途体力可以为负，最终的得分就是最后的体力值。</p><p>因为是在梦里，YouSiki的操作并不像清醒时那么行云流水，虽然不至于从板子中间掉落，但是也不能跳过某个板子，即他现在只能从第i个板子跳到第i+1个板子。</p><p>并且，智商超群的YouSiki还可以清醒的认识到自己正活在梦里，并且可以随时把自己惊醒。</p><p>现在他要开始挑战了，系统告诉他这一层一共有N个好板子和M个坏板子，而精通OI知识的YouSiki此刻却开始思考——如果他选择最优策略，那么其在被自己惊醒之前获得的得分期望是多少。</p><p>注意，因为YouSiki有严重的近视眼，所以他在第i层的时候并不会知道第i+1层是什么样的板子；还有，YouSiki甚至可以在一个板子都没有情况下就把自己惊醒。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>一行两个整数，N和M，分别代表好板子数量和坏板子数量。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一行一个小数，表示最优策略下的期望分数，四舍五入保留3位小数。<br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1.500</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>N,M &lt;= 5000</p>
</div>
</div>