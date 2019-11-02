<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>Magic Land 上的时间又过了若干世纪„„ <br> <br> 现在， 人们谈论着一个传说：从前，他们的祖先来到了一个位于东方的岛屿，<br>那里简直就是另外一个世界。善于分析与构造的 Magic Land 上的人们总是不明<br>白那里的人们是如何不借助精确的实验与计算驱动和操纵魔法。 <br> <br> 偶然地，一个魔法使（Magician）来到了Magic Land，在临走的时候留下了<br>一个神奇的盒子，叫做星之器（Casket of star）。 <br> 虽然不知道这个盒子是做什么的，但是经过了大量的实验和计算后，人们已<br>经清楚它的一些事实： <br> 1．星之器之中有N×M 个区域，可看作分成 N行和 M列的格子，每个区域<br>之中有若干单位的称为“星”的对象，这个对象的最小单位已经被确定，所以，<br>这个数量总是整数。 <br> 2．魔法使可以驱动星之器中位于同一行或同一列的不相邻（有公共边的区<br>域称为相邻的）两个区域中各 1 单位的“星”，使得它们分别向中心移动 1 格。 <br> 3．每一次使用2 中的方法驱动“星”，将会产生魔力，魔法使会得到这一部<br>分魔力。魔力的量等于这个两个区域之间所间隔的区域数。</p>
<p>这样，我们可以用一个 N×M 的数表来表示星之器的状态，比如 N=2，M=3<br>时： <br> <br>2 0 1                                     1 2 0 <br>5 1 4                                     5 1 4 <br> <br>当星之器为左图的状态时，通过操纵第一行的第 1 和3 个区域中的“星” （加<br>粗的数字对应的区域），变为右图所示的状态，同时，将产生 1 单位的魔力（因<br>为这两个区域之间恰好隔了 1 个区域）。 <br> <br> 在经过了进一步的研究之后，人们知道了这个星之器最初的状态（Ini）以及<br>最终被他们得到时的状态（Fin）。 <br> 你希望知道，星之器最多帮助它的拥有者提供了多少的魔力。即：经过一系<br>列上述操作由初态（Ini）变为终态（Fin） ，至多产生多少魔力。 <br> 需要注意的是，显然操作过程中每个区域内“星”的数量不能是负的，即：<br>如果那个区域已经没有“星”了，当然就不能继续操作了。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行包含两个正整数N、M 表示星之器的大小。 <br>接下来的N 行，每行包含 M个自然数：Iniij，描绘了初态（Ini）。 <br>在一个空行后的N 行，每行包含 M 个自然数：Fin ，描绘了终态（Fin） 。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出一个正整数，表示至多产生的魔力。&nbsp;</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>5 5 <br>1 0 0 0 1 <br>0 0 0 0 0 <br>0 0 0 0 0 <br>0 1 0 1 1 <br>1 0 0 0 0 <br> <br>0 0 0 0 0 <br>0 0 0 0 1 <br>2 0 0 0 1 <br>0 0 2 0 0 <br>0 0 0 0 0</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>7</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>40%的数据中N ≤ 2，如样例2； <br>100%的数据中1 ≤ N，M ≤ 200，Iniij，Finij ≤ 1000。 <br> 所有数据保证了至少存在一个操作方法使得星之器由初态变为终态，同时保<br>证了初态与终态不是完全相同的。</p>
</div>
</div>