
# Description

<div class="content"><div>
<div>Jill在骑车周游Warsaw时，偶然发现一家销售有趣的玻璃瓶的商店。她认为用这些瓶子测量液体可能是一个有趣的</div>
<div>计划，但是这需要在瓶子上做一些标记来指示各个体积。这些标记应该如何标在哪里呢？Jill将问题正式化如下。</div>
<div>假设瓶子是由一条从X=Xlow到X=Xhigh的多项式曲线绕X轴旋转一周构成。因此，X轴与一条穿过瓶子底面中心的垂</div>
<div>线重合。瓶底在X=Xlow由一个实心圆构成，瓶口在X=Xhigh，瓶口是敞开的。第一个样例表示瓶子由从Xlow=0到Xhi</div>
<div>gh=12的多项式4-0.25X构成。瓶子的底部是一个半径为4的圆，瓶口是一个半径为1的圆。瓶子的高度是12。体积每</div>
<div>增加25做一次增量标记。给定多项式P，Xlow，Xhigh，并给定瓶子上连续的两个标记间的体积增量，计算标记与Xl</div>
<div>ow之间的距离。标记不能被标在瓶口以上的位置，标记的数量不能超过8个。</div>
</div>
<div></div>
<p></p></div>

# Input

<div class="content"><div>
<div>第一行1个整数n，表示多项式的次数。</div>
<div>第二行n+1个数，表示a0,a1,a2…an，为多项式P的实数系数，它们决定了瓶子的形状。 a0为常数项，a1为1次项系数……an为n次项系数。</div>
<div>第三行3个数，Xlow，Xhigh两个实数表示瓶底位置和瓶口位置。inc，一个整数表示每连续两个标记间体积的增量是多少。</div>
<div>0&lt;=n&lt;=10，-100&lt;=ai&lt;=100，an不等于0，-100&lt;=Xlow&lt;Xhigh&lt;=100，Xhigh-Xlow&gt;0.1，1&lt;=inc&lt;=500，</div>
<div>输入保证所有标记与瓶子顶部的距离不会小于0.01，瓶子的体积不超过1000，</div>
<div>四舍五入后任意两个标记间的距离至少为0.05，对于任意X满足Xlow&lt;=X&lt;=Xhigh，P(X)&gt;0。</div>
</div>
<div></div>
<div></div>
<p></p></div>

# Output

<div class="content"><div>
<div>第一行输出整个瓶子的体积。</div>
<div>第二行输出一个长度不超过8的递增序列，依次表示从瓶底开始（不含瓶底）的连续标记距离瓶底的距离。</div>
<div>体积和所有标记的距离精确到小数点后两位。</div>
<div>如果没有标记，输出” insufficient volume”（不含引号）。</div>
</div>
<div></div>
<p></p></div>

# Sample Input

<div class="content"><span class="sampledata">1<br/>
5.0 -1.0<br/>
0.0 4.0 50</span></div>

# Sample Output

<div class="content"><span class="sampledata">Case 1: 129.85<br/>
0.74 1.91</span></div>

# Hint

<div class="content"><p></p><p>请不要提交，尚无SPJ</p><br/>
<p></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

