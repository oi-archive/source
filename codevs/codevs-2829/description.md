<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    小林跟着银河队选手去了一趟宇宙比赛，耳濡目染，变得学术起来。回来后，他发现世界大变样了。比丘兽究级进化，成了凤凰兽；金先生因为发了一篇 paper，一跃成为教授，也成为了银河队选拔委员会成员。</p>
<p>    一日，小林与金教授聊天。金教授回忆起过去的岁月，那些年他学过的电路原理。他曾经对一种三角波很感兴趣，并且进行了一些探究。小林感到很好奇，于是金教授就将课题形式化地说了一遍。</p>
<p>    有一定义在[0, N]的连续函数 f(x)，其中 N 是整数，满足 f(0)=f(N)=0，它的所有极值点在整数处取到，且 f(x)的极小值均是 0。对于任意的 0 到 N-1 间的整数 I，f(x)在(I, I+1)上是斜率为 1 或-1 的一次函数。</p>
<p>    金先生研究的是，若他知道其中 K 个整点的函数值，那么：(1)有多少个函数满足条件？(2)满足条件的函数中，max f(x)最大能是多少？</p>
<p>    小林思考了一下，便想出了很好的算法。那么作为经过多年训练的你呢？ </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含 2 个用空格隔开的整数 N, K。接下来K 行，每行 2 个整数，表示 x[i]和 f(x[i])。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>仅一行，包含 2 个整数，分别对应两个问题的答案。考虑到第一问答案可能很大，你只要输出它除以 19940417 的余数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>2 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1 1</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于 10%的数据，N≤10。 <br>对于 20%的数据，N≤50。 <br>对于 30%的数据，N≤100, K≤100。 <br>对于 50%的数据，N≤1000, K≤1000。 <br>对于 70%的数据，N≤100000。 <br>另有 10%的数据，K=0。 <br>对于 100%的数据，0≤N≤1000000000，0≤K≤1000000。</p>
</div>
</div>