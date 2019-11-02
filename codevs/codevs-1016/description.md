<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    每样商品的价格越低，其销量就会相应增大。现已知某种商品的成本及其在若干价位上的销量（产品不会低于成本销售），并假设相邻价位间销量的变化<span style="text-decoration: underline;">是线性</span>的且在价格高于给定的最高价位后，销量以某固定数值递减。（我们假设价格及销售量都是整数）</p>
<p> </p>
<p>    对于某些特殊商品，不可能完全由市场去调节其价格。这时候就需要政府以税收或补贴的方式来控制。（所谓税收或补贴就是对于<span style="text-decoration: underline;">每个产品</span>收取或给予生产厂家固定金额的货币）</p>
<p>    你是某家咨询公司的项目经理，现在你已经知道政府对某种商品的预期价格，以及在各种价位上的销售情况。要求你确定政府对此商品是应收税还是补贴的<span style="text-decoration: underline;">最少</span>金额（也为整数），才能使商家在这样一种政府预期的价格上，获取相对其他价位上的最大<span style="text-decoration: underline;">总利润</span>。</p>
<p> </p>
<div>
<p>     <strong><em> </em></strong><strong><em>总利润       = 单位商品利润 * 销量 </em></strong></p>
<p><strong><em>     单位商品利润 = 单位商品价格 – 单位商品成本 （– 税金  or  + 补贴）</em></strong></p>
</div>
<p> </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>    输入的第一行为政府对某种商品的预期价，第二行有两个整数，第一个整数为商品成本，第二个整数为以成本价销售时的销量售，以下若干行每行都有两个整数，第一个为某价位时的单价，第二个为此时的销量，以一行-1，-1表示所有已知价位及对应的销量输入完毕，输入的最后一行为一个单独的整数表示在已知的最高单价外每升高一块钱将减少的销量。</p>
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

<p>&nbsp; &nbsp;输出有两种情况：若在政府预期价上能得到最大总利润，则输出一个单独的整数，数的正负表示是补贴还是收税，数的大小表示补贴或收税的金额最小值。若有多解，取绝对值最小的输出。</p>
<p>&nbsp;&nbsp;&nbsp;&nbsp; 如在政府预期价上不能得到最大总利润，则输出&ldquo;NO SOLUTION&rdquo;.</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>  31</p>
<p>  28 130</p>
<p>  30 120</p>
<p>  31 110</p>
<p>  -1 –1</p>
<p>  15</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>  4</p>

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