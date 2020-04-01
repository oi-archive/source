<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p> zms_和jyt是好(en)基(ai)友(gou)，有一天他们看到了一排$N$堆物品，zms_想从里面拿一点东西出来，送给jyt当生日礼物。<br>  为了简化题意（出题人太弱），我们认为每一堆物品中的所有物品都是同一种，并且每一堆都有无限个。<br>  总共有$M$种物品，任意两个同种物品可以看做是相同的，现在zms_想从中选出若干个排成一排，（物品的顺序不一定要按照它们在N堆石子中的顺序，参见样例）而为了jyt满意，zms_摆出来的物品必须是不规则的，即如果把K个物品看成一个长为K，字符集为M的字符串，则这个字符串不能由其中一个前缀重复若干次恰好得到（如果这个串是1,2,1,1,2,1，则不合法，因为可以由1,2,1重复两次得到；但1,2,1,2,1,则合法，因为除了它本身，不能由任何一个前缀重复若干次恰好得到，也就是说这个字符串的最小循环串必须是其本身）<br>  为了保密，这件事情只能在zms_和jyt从某一堆物品向右走的时候秘密进行，zms_和jyt的路线虽然是不固定的，但是一定是一段连续的区间。<br>  现在，zms_一共有Q条路线，对于第$i$条路线，zms_想选出$K_i$个物品。zms_希望你对于每条路线，计算出zms_摆出使jyt满意的K个物品的方案数，任意两个方案不同当且仅当存在一个位置上所放的物品种类不同，你只需要输出这个数对$10^9+7$取模之后的结果</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行三个整数$N,M,Q$<br>接下来一行$N$个整数，代表每一堆物品的种类<br>接下来$Q$行，每行三个整数，分别是$L,R,K$，表示每条路线的起点，终点，以及zms_想 选出的数的个数</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>总共$Q$行，每行一个整数表示答案</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 2 2<br>1 2 1<br>1 2 2<br>1 3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2<br>6</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于第一个询问，只有两种选择方案{2,1}{1,2}<br>对于第二个询问，{1,2,1}{1,1,2}{2,1,1}{2,1,2}{2,2,1},{1,2,2}</p><p> 对于30%的数据，$N,M,Q,K \leq 10$<br> 对于50%的数据，$N,M,Q,K \leq 100$<br> 对于100%的数据，$N,M,Q,K \leq 50000$</p>
</div>
</div>