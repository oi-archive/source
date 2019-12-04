<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p><em>A</em>公司正在热销某计算机产品，作为<em>A</em>公司CEO的小<em>A</em>打算为接下来连续的<em>N</em>个销售季度制定一份具体的生产和销售方案。已知第<em>i</em>个销售季度该产品的订购量为<em>D<sub>i</sub></em>，在第<em>i</em>个季度，<em>A</em>公司会通过如下几种方式来解决用户的订购需求：</p>
<p>l  在第<em>i</em>个季度生产新的产品来销售。</p>
<p>l  若在第<em>i</em>个季度以前库存还有多余的产品，则可以直接在第<em>i</em>个季度销售(注意第一个季度之前没有任何库存产品)。</p>
<p>l  在第<em>i</em>个季度可以不完成全部的订购需求，而将未完成的订购需求推迟，归入到下一个季度(<em>i</em> + 1)的产品订购需求中。</p>
<p><em>A</em>公司需要考虑以下几种耗费：<strong><span style="text-decoration: underline;">生产新产品的成本耗费</span></strong>、库存产品的<strong><span style="text-decoration: underline;">额外储存耗费</span></strong>以及推迟订购需求而需要<strong><span style="text-decoration: underline;">赔偿给用户的损失费</span></strong>。另外由于劳力和资源的限制，每个销售季度能够生产新产品的数量是有限的，各季度的耗费和可以生产的产品上限数也不尽相同，具体如下：</p>
<p>l  在第<em>i</em>个季度最多可以生产<em>U<sub>i</sub></em>件新的产品，每一件的成本为<em>P<sub>i</sub></em>。</p>
<p>l  第<em>i</em>个季度保存下来的产品，可以用于以后季度的销售。对于每一件产品，若从第<em>i</em>季度保存到第<em>i</em> + 1季度，需要额外支付<em>M<sub>i</sub></em>的存储费用(注意产品保存到下个季度后可能再次库存)。</p>
<p>l  对于第<em>i</em>个季度需要推迟而归入到下一个季度订购需求的每一件产品，<em>A</em>公司需要赔偿给用户损失费<em>C<sub>i</sub></em>(注意延迟到下个季度可能再次被延迟, 费用按后面季度的延迟费用计)。</p>
<p>在第<em>N</em>个季度结束后，<em>A</em>公司必须解决之前所有的用户订单。可以保证，<em>A</em>公司能够生产的产品总数不会低于总订购量，也就是说<strong>一定存在一组生产和销售方案使得满足所有的用户订购需求</strong>。小<em>A</em>想知道如何来安排产品的生产和销售，使得在满足所有订购需求的前提下公司总的耗费最小。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行是一个正整数<em>N</em>，表示有<em>N</em>个销售季度。</p>
<p>第二行有<em>N</em>个非负整数<em>D</em><sub>1</sub>, <em>D</em><sub>2</sub>, .., <em>D<sub>N</sub></em>，表示第<em>i</em>个季度的订购量。</p>
<p>第三行有<em>N</em>个非负整数<em>U</em><sub>1</sub>, <em>U</em><sub>2</sub>, .., <em>U<sub>N</sub></em>，表示第<em>i</em>个季度最多可以生产的新的产品数。</p>
<p>第四行有<em>N</em>个非负整数<em>P</em><sub>1</sub>, <em>P</em><sub>2</sub>, .., <em>P<sub>N</sub></em>，表示第<em>i</em>个季度生产一件新产品的成本。</p>
<p>第五行有<em>N</em> – 1个非负整数<em>M</em><sub>1</sub>, <em>M</em><sub>2</sub>, ..,<em>M<sub>N</sub></em><sub>-1</sub>，表示将一件产品从第<em>i</em>个季度保存到第<em>i </em>+1个季度所需要的额外的耗费。</p>
<p>第六行有<em>N</em>-1个非负整数<em>C</em><sub>1</sub>, <em>C</em><sub>2</sub>, .., <em>C<sub>N</sub></em><sub>-1</sub>，表示一件产品的订购需求在第<em>i</em>个季度没有完成而归入到第<em>i</em> +1个季度的订购量中，需要赔偿给用户的损失费。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>包含一个非负整数，表示公司的最小总耗费。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>4</p>
<p>3 2 1 2</p>
<p>2 5 2 2</p>
<p>5 1 5 5</p>
<p>1 2 1</p>
<p>5 3 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>30</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>对于30%的数据，<em>N</em> 1,000。</p>
<p>对于100%的数据，1 <em>N</em> 100,000，1<em>D<sub>i</sub></em>, <em>U<sub>i</sub></em>, <em>P<sub>i</sub></em>, <em>M<sub>i</sub></em><sub>,</sub><em>C<sub>i</sub></em> 10,000。</p>
</div>
</div>