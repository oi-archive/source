<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">金明今天很开心，家里购置的新房就要领钥匙了，新房里有一间他自己专用的很宽敞的房间。更让他高兴的是，妈妈昨天对他说：“你的房间需要购买哪些物品，怎么布置，你说了算，只要不超过</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">N</span></span></span><span style="">元钱就行”。今天一早金明就开始做预算，但是他想买的东西太多了，肯定会超过妈妈限定的</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">N</span></span></span><span style="">元。于是，他把每件物品规定了一个重要度，分为</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">5</span></span></span><span style="">等：用整数</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">1</span></span><span style=""><span style="font-family: Courier New,monospace;"><span style="">~</span></span></span><span style="font-family: Courier New,monospace;"><span style="">5</span></span></span><span style="">表示，第</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">5</span></span></span><span style="">等最重要。他还从因特网上查到了每件物品的价格（都是整数元）。他希望在不超过</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">N</span></span></span><span style="">元（可以等于</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">N</span></span></span><span style="">元）的前提下，使每件物品的价格与重要度的乘积的总和最大。</span></p>
<p style=""><span style="">设第</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">j</span></span></span><span style="">件物品的价格为</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">v[j]</span></span></span><span style="">，重要度为</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">w[j]</span></span></span><span style="">，共选中了</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">k</span></span></span><span style="">件物品，编号依次为</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Courier New,monospace;"><span style="">j</span></span></span><span style=""><sub><span style="font-family: Courier New,monospace;"><span style="">1</span></span></sub></span></span><span style=""><span style="">，</span></span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">j</span></span><sub><span style="font-family: Courier New,monospace;"><span style="">2</span></span></sub></span><span style="">，……，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">j</span></span><sub><span style="font-family: Courier New,monospace;"><span style="">k</span></span></sub></span><span style="">，则所求的总和为：</span></p>
<p style=""><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style=""><span>v[j</span></span></span><sub><span style="font-family: Courier New,monospace;"><span style=""><span>1</span></span></span></sub><span style="font-family: Courier New,monospace;"><span style=""><span>]*w[j</span></span></span><sub><span style="font-family: Courier New,monospace;"><span style=""><span>1</span></span></span></sub><span style="font-family: Courier New,monospace;"><span style=""><span>]+v[j</span></span></span><sub><span style="font-family: Courier New,monospace;"><span style=""><span>2</span></span></span></sub><span style="font-family: Courier New,monospace;"><span style=""><span>]*w[j</span></span></span><sub><span style="font-family: Courier New,monospace;"><span style=""><span>2</span></span></span></sub><span style="font-family: Courier New,monospace;"><span style=""><span>]+</span></span></span><span style=""><span style="">…</span></span><span style="font-family: Courier New,monospace;"><span style=""><span>+v[j</span></span></span><sub><span style="font-family: Courier New,monospace;"><span style=""><span>k</span></span></span></sub><span style="font-family: Courier New,monospace;"><span style=""><span>]*w[j</span></span></span><sub><span style="font-family: Courier New,monospace;"><span style=""><span>k</span></span></span></sub><span style="font-family: Courier New,monospace;"><span style=""><span>]</span></span></span></span><span style="">。（其中</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">*</span></span></span><span style="">为乘号）</span></p>
<p style=""><span style="">请你帮助金明设计一个满足要求的购物单。</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p style=""><span style="">输入</span><span style="">的第</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">1</span></span></span><span style="">行，为两个正整数，用一个空格隔开：</span><span style="font-family: Courier New,monospace;"><span style="">N m</span></span></p>
<p style=""><span style="">（其中</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">N</span></span></span><span style=""><span style="">（</span></span><span style="font-family: DejaVu Serif Condensed,serif;"><span style=""><span style="font-family: Courier New,monospace;"><span style="">&lt;</span></span></span><span style="font-family: Courier New,monospace;"><span style="">30000</span></span></span><span style="">）表示总钱数，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">m</span></span></span><span style="">（</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">&lt;25</span></span></span><span style="">）为希望购买物品的个数。）</span></p>
<p style=""><span style="">从第</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">2</span></span></span><span style="">行到第</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">m+1</span></span></span><span style="">行，第</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">j</span></span></span><span style="">行给出了编号为</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">j-1</span></span></span><span style="">的物品的基本数据，每行有</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">2</span></span></span><span style="">个非负整数</span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style="">v p</span></span></p>
<p style=""><span style="">（其中</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">v</span></span></span><span style="">表示该物品的价格</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">(v&lt;=10000)</span></span></span><span style="">，</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">p</span></span></span><span style="">表示该物品的重要度</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="">(1~5)</span></span></span><span style="">）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p style="text-indent: 0.19cm; margin-top: 0.49cm; margin-bottom: 0.49cm; line-height: 0.64cm; widows: 2; orphans: 2;" align="left"><span style="font-size: small;">输出</span><span style="font-size: small;">只有一个正整数，为不超过总钱数的物品的价格与重要度乘积的总和的最大值（</span><span style="font-family: DejaVu Serif Condensed,serif;"><span style="font-family: Courier New,monospace;"><span style="font-size: small;">&lt;100000000</span></span></span><span style="font-size: small;">）。</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: Courier New,monospace;">1000 5</span></p>
<p style=""><span style="font-family: Courier New,monospace;">800 2</span></p>
<p style=""><span style="font-family: Courier New,monospace;">400 5</span></p>
<p style=""><span style="font-family: Courier New,monospace;">300 5</span></p>
<p style=""><span style="font-family: Courier New,monospace;">400 3</span></p>
<p style=""><span style="font-family: Courier New,monospace;">200 2</span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>3900</p>

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