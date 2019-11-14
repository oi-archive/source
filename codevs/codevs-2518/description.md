<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>渐渐地，Magic Land 上的人们对那座岛屿上的各种现象有了深入的了解。 <br> <br> 为了分析一种奇特的称为梦想封印（Fantasy Seal）的特技，需要引入如下的<br>概念： <br> 每一位魔法的使用者都有一个“魔法脉络”，它决定了可以使用的魔法的种<br>类。 <br> 一般地，一个“魔法脉络”可以看作一个无向图，有N 个结点及 M 条边，<br>将结点编号为1~N，其中有一个结点是特殊的，称为核心（Kernel），记作 1 号<br>结点。每一条边有一个固有（即生成之后再也不会发生变化的）权值，是一个不<br>超过U 的自然数。 <br> 每一次魔法驱动，可看作是由核心（Kernel）出发的一条有限长的道路（Walk），<br>可以经过一条边多次，所驱动的魔法类型由以下方式给出： <br> 将经过的每一条边的权值异或（xor）起来，得到s。 <br> 如果 s是 0，则驱动失败，否则将驱动编号为 s 的魔法（每一个正整数编号<br>对应了唯一一个魔法）。 <br> 需要注意的是，如果经过了一条边多次，则每一次都要计入 s中。 <br> 这样，魔法脉络决定了可使用魔法的类型，当然，由于魔法与其编号之间的<br>关系尚未得到很好的认知，此时人们仅仅关注可使用魔法的种类数。</p>
<p>梦想封印可以看作是对“魔法脉络”的破坏： <br> 该特技作用的结果是，“魔法脉络”中的一些边逐次地消失。 <br> 我们记总共消失了Q 条边，按顺序依次为 Dis1、Dis2、„„、DisQ。 <br> <br> 给定了以上信息，你要计算的是梦想封印作用过程中的效果，这可以用 Q+1<br>个自然数来描述： <br> Ans0为初始时可以使用魔法的数量。 <br> Ans1为Dis1被破坏（即边被删去）后可以使用魔法的数量。 <br> Ans2为Dis1及Dis2均被破坏后可使用魔法的数量。 <br> „„ <br> AnsQ为Dis1、Dis2、„„、DisQ全部被破坏后可以使用魔法的数量。 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含三个正整数N、M、Q。 <br>接下来的 M 行，每行包含 3 个整数，Ai、Bi、Wi，表示一条权为 Wi的与结<br>点Ai、Bi关联的无向边，其中 Wi是不超过U 的自然数。 <br>接下来 Q行，每行一个整数：Dis。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>一共包Q+1 行，依次为Ans0、Ans1、&bdquo;&bdquo;、AnsQ。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 3 2 <br>1 2 1 <br>2 3 2 <br>3 1 4 <br>1 <br>3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>5<br>2<br>0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>所有数据保证该无向图不含重边、自环。 <br>所有数据保证不会有一条边被删除多次，即对于不同i 和 j，有Disi≠Disj <br>30%的数据中N ≤ 50，M ≤ 50，Q ≤50，U≤100； <br>60%的数据中N ≤ 300，M ≤ 300，Q ≤50，U≤109<br>； <br>80%的数据中N ≤ 300，M ≤ 5000，Q ≤5000，U≤1018<br>； <br>100%的数据中N ≤ 5000，M ≤ 20000，Q ≤20000，U≤1018<br>；</p>
</div>
</div>