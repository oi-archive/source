<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>现在是晚餐时间,而母牛们在外面分散的牧场中。 农民约翰按响了电铃,所以她们开始向谷仓走去。 你的工作是要指出哪只母牛会最先到达谷仓(在给出的测试数据中,总会有且只有一只最快的母牛)。 在挤奶的时候(晚餐前),每只母牛都在她自己的牧场上,一些牧场上可能没有母牛。 每个牧场由一条条道路和一个或多个牧场连接(可能包括自己)。 有时，两个牧场(可能是字母相同的)之间会有超过一条道路相连。 至少有一个牧场和谷仓之间有道路连接。 因此,所有的母牛最后都能到达谷仓,并且母牛总是走最短的路径。 当然,母牛能向着任意一方向前进,并且她们以相同的速度前进。 牧场被标记为'a'..'z'和'A'..'Y',在用大写字母表示的牧场中有一只母牛,小写字母中则没有。 谷仓的标记是'Z',注意没有母牛在谷仓中。</p>
<p><strong>注意'm'和'M'不是同一个牧场</strong><strong>否则错误</strong>上面的意思是说：输入数据中可能会同时存在M,m（郁闷ing)，比如</p>
<p>M a a m m z</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第 1 行: 整数 P(1&lt;= P&lt;=10000),表示连接牧场(谷仓)的道路的数目。</p>
<p>第 2 ..P+1行:  用空格分开的两个字母和一个整数:</p>
<p>被道路连接牧场的标记和道路的长度(1&lt;=长度&lt;=1000)。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>单独的一行包含二个项目:最先到达谷仓的母牛所在的牧场的标记,和这只母牛走过的路径的长度。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5</p>
<p>A d 6</p>
<p>B d 3</p>
<p>C e 9</p>
<p>d Z 8</p>
<p>e Z 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>B 11</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">

</div>
</div>