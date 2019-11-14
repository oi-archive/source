<div class="panel panel-default">
<div class="area-title">
<span>
题目描述
<small>Description</small>
</span></div>
<div class="panel-body">

<p>小 Y 最近在一家金券交易所工作。该金券交易所只发行交易两种金券：A 纪 念券（以下简称 A 券）和 B 纪念券（以下简称 B 券）。每个持有金券的顾客都有 一个自己的帐户。金券的数目可以是一个实数。 每天随着市场的起伏波动，两种金券都有自己当时的价值，即每一单位金券 当天可以兑换的人民币数目。我们记录第 K 天中 A 券和 B 券的价值分别为 AK和 BK（元/单位金券）。 为了方便顾客，金券交易所提供了一种非常方便的交易方式：比例交易法。 比例交易法分为两个方面： a) 卖出金券：顾客提供一个[0，100]内的实数 OP 作为卖出比例，其意 义为：将 OP%的 A 券和 OP%的 B 券以当时的价值兑换为人民币； b) 买入金券：顾客支付 IP 元人民币，交易所将会兑换给用户总价值为 IP 的金券，并且，满足提供给顾客的 A 券和 B 券的比例在第 K 天恰好为 RateK； <br>例如，假定接下来 3 天内的 Ak、Bk、RateK的变化分别为：</p>
<table border="0">
<tbody>
<tr>
<td>时间</td>
<td>Ak</td>
<td>Bk</td>
<td>Ratek</td>
</tr>
<tr>
<td>第一天</td>
<td>1</td>
<td>1</td>
<td>1</td>
</tr>
<tr>
<td>第二天</td>
<td>1</td>
<td>2</td>
<td>2</td>
</tr>
<tr>
<td>第三天</td>
<td>2</td>
<td>2</td>
<td>3</td>
</tr>
</tbody>
</table>
<p>假定在第一天时，用户手中有 100 元人民币但是没有任何金券。 用户可以执行以下的操作：</p>
<table border="0">
<tbody>
<tr>
<td>时间</td>
<td>用户操作</td>
<td>人民币(元)</td>
<td> A 券的数量</td>
<td> B 券的数量</td>
</tr>
<tr>
<td>开户</td>
<td>无</td>
<td>100</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>第一天</td>
<td>买入100 元</td>
<td>0</td>
<td>50</td>
<td>50</td>
</tr>
<tr>
<td>第二天</td>
<td>卖出 50%</td>
<td>75</td>
<td>25</td>
<td>25</td>
</tr>
<tr>
<td>第二天</td>
<td>买入60 元</td>
<td>15</td>
<td>55</td>
<td>40</td>
</tr>
<tr>
<td>第三天 </td>
<td>卖出 100%</td>
<td>205</td>
<td>0</td>
<td>0</td>
</tr>
</tbody>
</table>
<p>注意到，同一天内可以进行多次操作。 <br>小 Y 是一个很有经济头脑的员工，通过较长时间的运作和行情测算，他已经 知道了未来 N 天内的 A 券和 B 券的价值以及 Rate。他还希望能够计算出来，如 果开始时拥有 S 元钱，那么 N 天后最多能够获得多少元钱。</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
输入描述
<small>Input Description</small>
</span></div>
<div class="panel-body">
<p>第一行两个正整数 N、S，分别表示小 Y 能预知的天数以及初始时拥有的钱数。<br>接下来 N 行，第 K 行三个实数 AK、BK、RateK，意义如题目中所述。</p>

</div>
</div>
<div  class="panel panel-default">
<div class="area-title">
<span>
输出描述
<small>Output Description</small>
</span></div>
<div class="panel-body">

<p>只有一个实数 MaxProfit，表示第 N 天的操作结束时能够获得的最大的金钱 数目。答案保留 3 位小数。</p>

</div>
</div>


<div class="panel panel-default">
<div class="area-title">
<span>
样例输入
<small>Sample Input</small>
</span></div>
<div class="panel-body">
<p>3 100</p>
<p>1 1 1</p>
<p>1 2 2</p>
<p>2 2 3</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
样例输出
<small>Sample Output</small>
</span></div>
<div class="panel-body">
<p>225.000</p>

</div>
</div>

<div class="panel panel-default">
<div class="area-title">
<span>
数据范围及提示
<small>Data Size & Hint</small>
</span></div>
<div class="panel-body">
<p>测试数据设计使得精度误差不会超过 10<sup>-7</sup>。</p>
<p>对于 40%的测试数据，满足 N ≤ 10；</p>
<p>对于 60%的测试数据，满足 N ≤ 1 000；</p>
<p>对于 100%的测试数据，满足 N ≤ 100 000； <br>对于 100%的测试数据，满足： 0 &lt; AK ≤ 10； 0 &lt; BK ≤ 10； 0 &lt; RateK ≤ 100；MaxProfit ≤ 109；</p>
<p> </p>
<p>样例说明</p>
<p>   开户 无 100 0 0 第一天 买入 100 元 0 50 50 第二天 卖出 100% 150 0 0 第二天 买入 150 元 0 75 37.5 第三天 卖出 100% 225 0 0</p>
<table border="0">
<tbody>
<tr>
<td>时间</td>
<td>用户操作</td>
<td>人民币(元)</td>
<td>A 券的数量</td>
<td>B 券的数量</td>
</tr>
<tr>
<td>开户</td>
<td>无</td>
<td>100</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>第一天</td>
<td>买入100元</td>
<td>0</td>
<td>50</td>
<td>50</td>
</tr>
<tr>
<td>第二天</td>
<td>卖出100%</td>
<td>150</td>
<td>0</td>
<td>0</td>
</tr>
<tr>
<td>第二天</td>
<td>买入150元</td>
<td>0</td>
<td>75</td>
<td>37.5</td>
</tr>
<tr>
<td>第三天</td>
<td>卖出100%</td>
<td>225</td>
<td>0</td>
<td>0</td>
</tr>
</tbody>
</table>
</div>
</div>