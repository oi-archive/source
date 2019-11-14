<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>宝库之门打开了，里面真的由无数的宝贝，小可可和你万分幸喜。除了各式各样的财宝以外，小可可在宝库的一角发现了一个迷宫。在这个迷宫里有N个开阔地，不妨将它们标号为1,2,……,N. 每两个的开阔地之间都有一来一回两条不同的小道相通，上面长了一些蘑菇，这种蘑菇十分神奇，被采摘后，还会立即长出来一样的蘑菇，而且每个蘑菇都有一定的价值（可能为负价值）。小可可非常喜欢这种神奇的蘑菇，于是马上就开始了采摘。</p>
<p>当小可可从开阔地i走到开阔地j时（i和j可以相等），他都将这条道上的蘑菇摘光，而在这条路上的蘑菇的价值为P<sub>ij</sub>。小可可不在路上停留，也就是说他经过某条路时只能且必须采摘一次。<strong>注意，从i走到j，与j走到i不是一条小道。</strong></p>
<p>小可可希望你能帮助他找到一条路程，使得他得到的蘑菇总价值与2007相差最小（即所有采摘的蘑菇的价值总和减去2007后的差的绝对值最小），他可以选择任意一个开阔地作为自己的出发点。由于你们的时间有限，所以小可可的总路程中<strong>只能恰好包含N条路（允许存在重复的路线）</strong>。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>输入文件第一行只有一个数字N(1&lt;=N&lt;=10).</p>
<p>下面有N行，每行有N个数字。其中第i行第j个实数代表P<sub>ij</sub>(-1,000,000&lt;=P<sub>ij</sub>&lt;=1,000,000).</p>
<p> </p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>你的程序只需要输出一个实数（精确到小数点后两位），即你找到的最优路程中蘑菇的总价值与2007的差的绝对值。</p>

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
<p>－1000.1 500.0</p>
<p>1507.0 1000.0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>0.00</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>见题面</p>
</div>
</div>