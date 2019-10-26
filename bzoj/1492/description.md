
# Description

<div class="content"><div>小Y最近在一家金券交易所工作。该金券交易所只发行交易两种金券：A纪念券（以下简称A券）和 B纪念券（以下</div>
<div>简称B券）。每个持有金券的顾客都有一个自己的帐户。金券的数目可以是一个实数。每天随着市场的起伏波动，</div>
<div>两种金券都有自己当时的价值，即每一单位金券当天可以兑换的人民币数目。我们记录第 K 天中 A券 和 B券 的</div>
<div>价值分别为 AK 和 BK（元/单位金券）。为了方便顾客，金券交易所提供了一种非常方便的交易方式：比例交易法</div>
<div>。比例交易法分为两个方面：（a）卖出金券：顾客提供一个 [0,100] 内的实数 OP 作为卖出比例，其意义为：将</div>
<div> OP% 的 A券和 OP% 的 B券 以当时的价值兑换为人民币；（b）买入金券：顾客支付 IP 元人民币，交易所将会兑</div>
<div>换给用户总价值为 IP 的金券，并且，满足提供给顾客的A券和B券的比例在第 K 天恰好为 RateK；例如，假定接</div>
<div>下来 3 天内的 Ak、Bk、RateK 的变化分别为：</div>
<div><img src="/source/bzoj/1492/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC9kZCgxKS5wbmc=.png" width="592" height="104" alt=""/></div>
<div>假定在第一天时，用户手中有 100元 人民币但是没有任何金券。用户可以执行以下的操作：</div>
<div><img src="/source/bzoj/1492/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC9kZCgyKS5wbmc=.png" width="587" height="144" alt=""/></div>
<div>
<div>注意到，同一天内可以进行多次操作。小Y是一个很有经济头脑的员工，通过较长时间的运作和行情测算，他已经</div>
<div>知道了未来N天内的A券和B券的价值以及Rate。他还希望能够计算出来，如果开始时拥有S元钱，那么N天后最多能</div>
<div>够获得多少元钱。</div>
</div>
<p></p></div>

# Input

<div class="content"><div>
<div>输入第一行两个正整数N、S，分别表示小Y能预知的天数以及初始时拥有的钱数。接下来N行，第K行三个实数AK、B</div>
<div>K、RateK，意义如题目中所述。对于100%的测试数据，满足：0&lt;AK≤10；0&lt;BK≤10；0&lt;RateK≤100；MaxProfit≤1</div>
<div>0^9。</div>
<div>【提示】</div>
<div>1.输入文件可能很大，请采用快速的读入方式。</div>
<div>2.必然存在一种最优的买卖方案满足：</div>
<div>每次买进操作使用完所有的人民币；</div>
<div>每次卖出操作卖出所有的金券。</div>
</div>
<div></div></div>

# Output

<div class="content"><p>只有一个实数MaxProfit，表示第N天的操作结束时能够获得的最大的金钱数目。答案保留3位小数。</p></div>

# Sample Input

<div class="content"><span class="sampledata">3 100<br/>
1 1 1<br/>
1 2 2<br/>
2 2 3</span></div>

# Sample Output

<div class="content"><span class="sampledata">225.000</span></div>

# Hint

<div class="content"><p></p><p><img src="/source/bzoj/1492/img/aHR0cHM6Ly9seWRzeS5jb20vSnVkZ2VPbmxpbmUvdXBsb2FkLzIwMTYwNC9kZCgzKS5wbmc=.png" width="595" height="155" alt=""/></p><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search="></a></p></div>

