<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>     Mafia是一种社会游戏。通常会在高中、夏令营和冬令营、国家竞赛中出现，通常游戏形式在晚上很晚的时候喝各种水果味汽水。这个游戏不在于赢，而在于参与比赛。</p><p>    为了解决这个问题，你不需要知道mafia的规则，所有你需要知道的是：一些选手是“歹徒”，剩下的是“平民”。歹徒们知道每个人是谁，但是平民们不知道。平民们试图在游戏中辨明谁是歹徒。</p><p>     在目前的一轮游戏中，有N个玩家，每个人已经指认了其他一个玩家是歹徒。<span style="text-decoration: underline;"><strong>平民们只是猜测谁是歹徒，而真正的歹徒一定指认一个平民却还假装不知道</strong></span>。</p><p>虽然不知道谁是歹徒，但是知道谁指认了谁，请确定在所有可行方案中，这些玩家中最多有几个歹徒。</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>   输入第一行包括一个偶数N（2≤N≤500000），表示玩家的数量。玩家依次按照1到N编号。</p><p>    接下来的N行中，每行包括一个整数，依次表示编号1到N的玩家指认的玩家编号（没有玩家会指认自己）。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出在所有玩家中最多可能有几个歹徒。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>2</p><p>1</p><p>1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>【样例解释】</p><p>第一个样例：歹徒可能是玩家2和3。</p><p>【数据范围】</p><p>40%的数据中，N＜15。</p><p>80%的数据中，N≤2000。</p><p><br></p>
</div>
</div>