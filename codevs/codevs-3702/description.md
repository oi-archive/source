<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">在市场上有很多商品的定价类似于</span> 999 <span style="">元、</span>4999 <span style="">元、</span>8999 <span style="">元这样。它们和</span> 1000 <span style="">元、</span>5000 <span style="">元和</span> 9000 <span style="">元并没有什么本质区别，但是在心理学上会让人感觉便宜很多，因此也是商家常用的价格策略。不过在你看来，这种价格十分荒谬。于是你如此计算一个价格</span> p<span style="">（</span>p <span style="">为正整数）的荒谬程度：</span></p><p style="">1<span style="">、首先将</span> p <span style="">看做一个由数字组成的字符串（不带前导</span> 0<span style="">）；</span></p><p style="">2<span style="">、然后，如果</span> p <span style="">的最后一个字符是</span> 0<span style="">，就去掉它。重复这一过程，直到</span> p <span style="">的最后一个字符不是</span> 0<span style="">；</span></p><p style="">3<span style="">、记</span> p <span style="">的长度为</span> a<span style="">，如果此时</span> p <span style="">的最后一位是</span> 5<span style="">，则荒谬程度为</span> 2 * a - 1<span style="">；否则为</span> 2 * a<span style="">。</span></p><p style=""><span style="">例如，</span>850 <span style="">的荒谬程度为</span> 3<span style="">，而</span> 880 <span style="">则为</span> 4<span style="">，</span>9999 <span style="">的荒谬程度为</span> 8<span style="">。</span></p><p style=""><span style="">现在，你要出售一样闲置物品，你能接受的定价在</span> [L, R] <span style="">范围内，你想要给出一个荒谬度最低的价格。</span></p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入文件的第一行包含一个正整数</span> T<span style="">，表示测试数据的数目。</span></p><p><span style="">每个测试数据占单独的一行，包含两个空格分隔的正整数</span> L, R<span style="">，表示定价的区间。</span></p><p><br></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent:28px"><span style="font-family:宋体">对于每个测试数据，在单独的一行内输出结果。如果荒谬度最低的价格不唯一，输出最小的那个。</span></p><p><br/></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3</p><p>998 1002</p><p>998 2002</p><p>4000 6000</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>1000</p><p>1000</p><p>5000</p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p><span style="">对于</span> 20% <span style="">的数据，</span>L, R <span style="">≤</span> 2000.</p><p><span style="">对于</span> 100% <span style="">的数据，</span>T <span style="">≤</span> 100<span style="">，</span>1 <span style="">≤</span> L <span style="">≤</span> R <span style="">≤</span> 10^9.</p><p><br></p>
</div>
</div>