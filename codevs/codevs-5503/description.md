<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>炉石传说是一款卡牌游戏，玩家通过卡牌随从与对方对战。</p><p>克苏恩（C'Thun）是一个上古之神，它出现后，会对敌方所有存活的随从和你的英雄（英雄死了即为失败）随机造成共N点伤害。</p><p><img src="/source/codevs/codevs-5503/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy01NTAzL2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvMWM5NTBhN2IwMjA4N2JmNDdkYTJjNjg1ZmFkMzU3MmMxMWRmY2YxNF8yMDE2MTExNTA3MDUyMF8xMDQuanBn.jpg" title=""></p><p>伤害会分次打出（即N总伤害=1点伤害*N次攻击），也就是说在敌方一个随从被杀死后，C'Thun不会再对它进行攻击。</p><p>如果你在该回合未能击败对方（杀死对方英雄），那么他的随从下一回合就会攻击你的英雄。  <br></p><p>若对方在他的回合内未能击败你，则视为你杀死对方英雄，即你胜利。<br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>现在给你克苏恩的攻击力（即N点伤害）    你的血量    对方血量</p><p>随从个数m<br></p><p>接下来m行分别为第i个随从的攻击力    血量<br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>第一行输出m个数 分别表示每个随从被消灭的可能性</p><p>第二行输出你的胜率</p><p>（所有概率以即约真分数形式表示）</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>例1:</p><p>3 3 3</p><p>2</p><p>2 1</p><p>3 1</p><p>例2:</p><p>3 1 2</p><p>2</p><p>2 1</p><p>3 1</p><p>例3:</p><p>3 2 3</p><p>2</p><p>2 1</p><p>3 1</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>例1:</p><p>4/13</p><p>4/13</p><p>10/13<br></p><p>例2:</p><p>1/4</p><p>1/4</p><p>1/1</p><p>例3:</p><p>4/13</p><p>4/13</p><p>7/13</p><p><br></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>没有任何套路<br></p>
</div>
</div>