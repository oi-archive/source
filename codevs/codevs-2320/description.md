<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>著名的生物学家赫伯特·格林斯大福最近发现了一种新型生物，名叫“the Graphius Vulgaris”，是一种在斯洛伐克西部Pesinza Baba野生植物栖息地所特有的植物。这颗植物非常奇怪，第一眼看上去就像一个普通的灌木丛，当然，仔细观察的话，你会注意到它的结构比较复杂。当树上的两个枝条彼此接触时，他们可能连为一体。实际上，它们经常这样做，导致了这颗植物非常的密集且反复无常（若赫伯特不是一个生物学家而是一个计算机科学家的话，他可能会发现，当把这颗植物当作图的话，那这颗植物不再是“树”而是一个普通的无向联通图）。</p>
<p>一些天过去了，这颗植物再次被两个OIER发现，他们名叫Alice和Bob。你可能知道他们，因为他们就是用博弈游戏“虐人”而出名的。在发现这颗树之前，他们正在构思一个新的“虐人”游戏。而这颗可怜的树立即成为了这个游戏的平台。</p>
<p>给定一个N个点的无向联通图，节点被标号为1到N。无向图上的边代表树中的枝条，而节点1代表地面。两个玩家轮流进行操作，Alice先手。一次操作包含两个步骤：第一个步骤，玩家从图中选出一条边并在图中删除。第二个步骤，在第一个步骤完成后，将不与点1联通的部分删除。第一个不能进行操作的玩家则视为失败。你可以假设Alice和Bob都执行最优策略。</p>
<p>你的任务非常简单，你保存了case个这样的树用来给Alice和Bob破坏。对于每一颗树，你需要计算谁会赢。在你告诉他们真相之后，它们就没有必要破坏这些树了，这些珍贵的树就被保存下来了。赶快，这些树可是非常珍贵的！</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行一个整数，case。接下来的数据分为case组。</p>
<p>每一组的第一行两个整数，N和M。N为点数，M为边数。</p>
<p>接下来M行每行两个整数，代表无向图中的一条边。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p align="left">对于每一组数据，输出必胜的人的名字。若为Alice则输出"Alice"，否则输出"Bob"。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2</p>
<p> </p>
<p>8 7</p>
<p>1 2</p>
<p>1 3</p>
<p>3 4</p>
<p>1 5</p>
<p>5 6</p>
<p>6 7</p>
<p>7 8</p>
<p> </p>
<p>5 6</p>
<p>1 2</p>
<p>1 3</p>
<p>3 2</p>
<p>1 4</p>
<p>5 1</p>
<p>4 5</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>Alice</p>
<p>Bob</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<table border="1" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td valign="top" width="114">
<p>测试点</p>
</td>
<td valign="top" width="113">
<p>case</p>
</td>
<td valign="top" width="114">
<p>N</p>
</td>
<td valign="top" width="114">
<p>M</p>
</td>
<td valign="top" width="114">
<p>Hint</p>
</td>
</tr>
<tr>
<td valign="top" width="114">
<p>[1, 4]</p>
</td>
<td valign="top" width="113">
<p>0&lt;case&lt;=100</p>
</td>
<td valign="top" width="114">
<p>0&lt;N&lt;=100</p>
</td>
<td valign="top" width="114">
<p>M=N-1</p>
</td>
<td valign="top" width="114">
<p>保证原图为链</p>
</td>
</tr>
<tr>
<td valign="top" width="114">
<p>[5, 12]</p>
</td>
<td valign="top" width="113">
<p>0&lt;case&lt;=100</p>
</td>
<td valign="top" width="114">
<p>0&lt;N&lt;=1000</p>
</td>
<td valign="top" width="114">
<p>M=N-1</p>
</td>
<td valign="top" width="114">
<p>保证原图为树</p>
</td>
</tr>
<tr>
<td valign="top" width="114">
<p>[13, 20]</p>
</td>
<td valign="top" width="113">
<p>0&lt;case&lt;=100</p>
</td>
<td valign="top" width="114">
<p>0&lt;N&lt;=2000</p>
</td>
<td valign="top" width="114">
<p>0&lt;M&lt;=20000</p>
</td>
<td valign="top" width="114">
<p> </p>
</td>
</tr>
</tbody>
</table>
<p> </p>
</div>
</div>