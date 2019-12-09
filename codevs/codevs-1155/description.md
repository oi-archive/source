<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p style=""><span style="">金明今天很开心，家里购置的新房就要领钥匙了，新房里有一间金明自己专用的很宽敞的房间。更让他高兴的是，妈妈昨天对他说：“你的房间需要购买哪些物品，怎么布置，你说了算，只要不超过</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">元钱就行”。今天一早<span style="">，</span>金明就开始做预算了，他把想买的物品分为两类：主件与附件，附件是从属于某个主件的，下表就是一些主件与附件的例子：</span></p>
&lt;dl&gt;&lt;dd&gt;
&lt;colgroup&gt;&lt;col width="66"/&gt; &lt;col width="118"/&gt; &lt;/colgroup&gt;
<table cellpadding="7" cellspacing="0" style=""><tbody>
<tr valign="TOP">
<td style="" width="66">
<p style=""><span style="">主件</span></p>
</td>
<td style="" width="118">
<p style=""><span style="">附件</span></p>
</td>
</tr>
<tr valign="TOP">
<td style="" width="66">
<p style=""><span style="">电脑</span></p>
</td>
<td style="" width="118">
<p style=""><span style="">打印机，扫描仪</span></p>
</td>
</tr>
<tr valign="TOP">
<td style="" width="66">
<p style=""><span style="">书柜</span></p>
</td>
<td style="" width="118">
<p style=""><span style="">图书</span></p>
</td>
</tr>
<tr valign="TOP">
<td style="" width="66">
<p style=""><span style="">书桌</span></p>
</td>
<td style="" width="118">
<p style=""><span style="">台灯，文具</span></p>
</td>
</tr>
<tr valign="TOP">
<td style="" width="66">
<p style=""><span style="">工作椅</span></p>
</td>
<td style="" width="118">
<p style=""><span style="">无</span></p>
</td>
</tr>
</tbody>
</table>
&lt;/dd&gt;&lt;/dl&gt;
<p style=""><span style="">如果要买归类为附件的物品，必须先买该附件所属的主件。每个主件可以有</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">0</span></span></span></span><span style="">个、</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">个或</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">个附件。附件不再有从属于自己的附件。金明想买的东西很多，肯定会超过妈妈限定的</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">元。于是，他把每件物品规定了一个重要度，分为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">5</span></span></span></span><span style="">等：用整数</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span><span style=""><span style="font-family: Courier New,monospace;"><strong>~</strong></span></span><span style="font-family: Courier New,monospace;">5</span></span></span></span><span style="">表示，第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">5</span></span></span></span><span style="">等最重要。他还从因特网上查到了每件物品的价格（都是</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">10</span></span></span></span><span style="">元的整数倍）。他希望在不超过</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">元（可以等于</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">元）的前提下，使每件物品的价格与重要度的乘积的总和最大。</span></p>
<p style=""><span style="">设第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">j</span></span></span></span><span style="">件物品的价格为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">v[j]</span></span></span></span><span style="">，重要度为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">w[j]</span></span></span></span><span style="">，共选中了</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">k</span></span></span></span><span style="">件物品，编号依次为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style=""><span style="font-family: Courier New,monospace;">j</span></span><span style=""><sub><span style="font-family: Courier New,monospace;">1</span></sub></span></span></span></span><span style=""><span style="">，</span></span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">j</span><sub><span style="font-family: Courier New,monospace;">2</span></sub></span></span></span><span style="">，……，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">j</span><sub><span style="font-family: Courier New,monospace;">k</span></sub></span></span></span><span style="">，则所求的总和为：</span></p>
<p style=""><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">v[j</span><sub><span style="font-family: Courier New,monospace;">1</span></sub><span style="font-family: Courier New,monospace;">]*w[j</span><sub><span style="font-family: Courier New,monospace;">1</span></sub><span style="font-family: Courier New,monospace;">]+v[j</span><sub><span style="font-family: Courier New,monospace;">2</span></sub><span style="font-family: Courier New,monospace;">]*w[j</span><sub><span style="font-family: Courier New,monospace;">2</span></sub><span style="font-family: Courier New,monospace;">]+ </span><span style="">…</span><span style="font-family: Courier New,monospace;">+v[j</span><sub><span style="font-family: Courier New,monospace;">k</span></sub><span style="font-family: Courier New,monospace;">]*w[j</span><sub><span style="font-family: Courier New,monospace;">k</span></sub><span style="font-family: Courier New,monospace;">]</span></span></span></span><span style="">。（其中</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">*</span></span></span></span><span style="">为乘号）</span></p>
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
<p style=""><span style="">第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span></span></span></span><span style="">行，为两个正整数，用一个空格隔开：</span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>N m</span></span></span></p>
<p style=""><span style="">（其中</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">N</span></span></span></span><span style="">（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">&lt;32000</span></span></span></span><span style="">）表示总钱数，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">m</span></span></span></span><span style="">（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">&lt;60</span></span></span></span><span style="">）为希望购买物品的个数。）</span></p>
<p style=""><span style="">从第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">2</span></span></span></span><span style="">行到第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">m+1</span></span></span></span><span style="">行，第</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">j</span></span></span></span><span style="">行给出了编号为</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">j-1</span></span></span></span><span style="">的物品的基本数据，每行有</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">3</span></span></span></span><span style="">个非负整数</span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span style=""><span>v p q</span></span></span></p>
<p style=""><span style="">（其中</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">v</span></span></span></span><span style="">表示该物品的价格（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">v&lt;10000</span></span></span></span><span style="">），</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">p</span></span></span></span><span style="">表示该物品的重要度（</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">1</span><span style=""><span style="font-family: Courier New,monospace;"><strong>~</strong></span></span><span style="font-family: Courier New,monospace;">5</span></span></span></span><span style="">），</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">q</span></span></span></span><span style="">表示该物品是主件还是附件。如果</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">q=0</span></span></span></span><span style="">，表示该物品为主件，如果</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">q&gt;0</span></span></span></span><span style="">，表示该物品为附件，</span><span style="font-family: Times New Roman,serif;"><span style=""><span><span style="font-family: Courier New,monospace;">q</span></span></span></span><span style="">是所属主件的编号）</span></p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p class="cjk" style="text-indent: 0.19cm; margin-top: 0.49cm; margin-bottom: 0.49cm; line-height: 0.64cm; widows: 2; orphans: 2;" align="LEFT"><span style="font-size: small;">只有一个正整数，为不超过总钱数的物品的价格与重要度乘积的总和的最大值（</span><span style="font-family: Times New Roman,serif;"><span style="font-size: small;"><span lang="en-US"><span style="font-family: Courier New,monospace;">&lt;200000</span></span></span></span><span style="font-size: small;">）</span></p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p style=""><span style="font-family: Courier New,monospace;"><span>1000 5</span></span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span>800 2 0 <br></span></span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span>400 5 1</span></span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span>300 5 1</span></span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span>400 3 0</span></span></p>
<p style=""><span style="font-family: Courier New,monospace;"><span>500 2 0</span></span></p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>2200</p>

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