<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>    "低价购买"这条建议是在奶牛股票市场取得成功的一条规则。要想被认为是伟大的投资者，你必须遵循以下的问题建议：“低价购买；再低价购买”。每次你购买一支股票，你必须用低于你上次购买它的价格购买它。买的次数越多越好！你的目标是在遵循以上建议的前提下，求你最多能购买股票的次数。你将会得到一段时间内一支股票每天的出售价（MAXLONGINT 范围内的正整数），你可以选择在哪些天购买这支股票。每次购买都必须遵循“低价购买；再低价购买”的原则。写一程序计算最大购买次数。<br style="font-family: 'Times New Roman';">这里是某支股票的价格清单：<br style="font-family: 'Times New Roman';"><br style="font-family: 'Times New Roman';">日期　1　 2 3 4 5 6 7 8 9 10 11 12<br style="font-family: 'Times New Roman';">价格　68　69 54 64 68 64 70 67 78 62 98 87<br style="font-family: 'Times New Roman';"><br style="font-family: 'Times New Roman';">最优秀的投资者可以购买最多4次股票，可行方案中的一种是：<br style="font-family: 'Times New Roman';"><br style="font-family: 'Times New Roman';">日期 2 5 6 10<br style="font-family: 'Times New Roman';"><br style="font-family: 'Times New Roman';">价格 69 68 64 62 </p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行：N （1〈=N〈=5000），股票发行天数<br style="font-family: 'Times New Roman';">第二行：N个数，是每天的股票价格。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>输出文件仅一行包含两个数：最大购买次数和拥有最大购买次数的方案数（小于等于2当二种方案“看起来是一样”时（就是说它们构成的价格队列一样的时候），这2种方案被认为是相同的。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>12 68 69 54 64 68 64 70 67 78 62 98 87</pre><p> </p><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>   </p><pre>4 2</pre><p><br></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>1〈=N〈=5000</p>
</div>
</div>