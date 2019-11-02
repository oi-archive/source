<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>对于有两个玩家的，状态透明且状态转移确定的博弈游戏，博弈树是常用的分析工具。博弈树是一棵有根树，其中的节点为游戏的状态。若节点B 的父亲是A，则说明状态A 能通过一次决策转移到状态B。每个状态都有一个唯一的决策方，即这个状态下应该由哪一方做出决策。我们规定双方在任何时候都是轮流做出决策的，即树上相邻节点的决策方总是不相同的。在这个问题中，我们只关心两个玩家的胜负情况，且规定游戏不会出现平局。我们称两个玩家分别为黑方和白方，其中根节点的决策方为黑方。显然每个节点只有两个状态：黑方胜和白方胜。若某内节点（即存在后继节点的节点）的决策方为黑方，则该节点为黑方胜的充要条件为它的儿子中存在黑方胜的节点，反之亦然。求解博弈树即为判明博弈树根节点的状态。如果我们得知了所有叶节点（即无后继节点的节点）的状态，那么博弈树就很容易求解了。但是现在的情况是所有叶节点的状态均为未知的，需要进一步的计算。对于一个由叶节点构成的集合S，如果S 中的节点均被判明为黑方胜，就可以断言根节点为黑方胜的话，则称S 为一个黑方胜集合。对于黑方胜集合S，如果对于任意的黑方胜集合S’ 均满足|S| ≤ |S’ |（|S|表示集合S 中的元素数目），则称S 为一个最小黑方胜集合。同样地，也可以定义白方胜集合和最小白方胜集合。<br>Eden 最近在研究博弈树问题。他发现，如果一个叶节点既属于某一个最小黑方胜集合，又属于一个最小白方胜集合，那么求解这个节点的状态显然最有益于求解根节点的状态。像这样的叶节点就称之为关键叶节点。对于一棵给定的博弈树，Eden 想要知道哪些叶节点是关键叶节点。</p>

<img src="/source/codevs/codevs-1887/img/aHR0cDovL3d3dy5qb3lvaS5jbi9wcm9ibGVtL2NvZGV2cy0xODg3L2h0dHA6Ly9jb2RldnMuY24vbWVkaWEvaW1hZ2UvMTg4Ny5qcGc=.jpg" style="max-width:700px">

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>每个测试点包含一组测试数据。<br>测试数据的第一行包含一个正整数n，表示博弈树的节点数目。节点从1 到<br>n 编号，且1 号节点为根节点。<br>之后n – 1 行，每行包含一个正整数。第i 行的正整数表示节点i 的父节点的编号</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>在一行内输出三个空格分隔的正整数，分别是编号最小的关键叶节点的编号，<br />关键叶节点的数目和所有关键叶节点的编号的异或和。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>7<br>1<br>1<br>2<br>2<br>3<br>3 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>4 4 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>如图所示，黑色节点表示决策方为黑方的节点，反之亦然。<br>所有的最小黑方胜集合为{4, 5}和{6, 7}。<br>所有的最小白方胜集合为{4, 6}，{4, 7}，{5, 6}和{5, 7}。<br>所以关键叶节点的集合为{4, 5, 6, 7}。</p>
<p> </p>
<p>对于30% 的数据，n ≤ 100；<br>对于40% 的数据，n ≤ 1,000；<br>对于50% 的数据，n ≤ 10,000，且树是随机生成的；<br>对于100% 的数据，1 ≤ n ≤ 200,000，且对于节点i（i ≠ 1），其父节点的编号小于i。</p>
</div>
</div>