
# Description

<div class="content"><p><span style="font-size: medium">尽管奶牛们天生谨慎，她们仍然在住房抵押信贷市场中受到打击，现在她们开始着手于股市。 Bessie很有先见之明，她不仅知道今天S (2 &lt;= S &lt;= 50)只股票的价格，还知道接下来一共D(2 &lt;= D &lt;= 10)天的（包括今天）。 给定一个D天的股票价格矩阵（1 &lt;= 价格 &lt;= 1000）以及初始资金M(1 &lt;= M &lt;= 200,000)，求一个最优买卖策略使得最大化总获利。每次必须购买股票价格的整数倍，同时你不需要花光所有的钱（甚至可以不花）。这里约定你的获利不可能超过500,000。 考虑这个牛市的例子（这是Bessie最喜欢的）。在这个例子中，有S=2只股票和D=3天。奶牛有10的钱来投资。 今天的价格 | 明天的价格 | | 后天的价格 股票 | | | 1 10 15 15 2 13 11 20 　　以如下策略可以获得最大利润，第一天买入第一只股票。第二天把它卖掉并且迅速买入第二只，此时还剩下4的钱。最后一天卖掉第二只股票，此时一共有4+20=24的钱。 </span></p></div>

# Input

<div class="content"><p><span style="font-size: medium">* 第一行: 三个空格隔开的整数：S, D, M </span></p>
<p><span style="font-size: medium">* 第2..S+1行: 行s+1包含了第s只股票第1..D天的价格 </span></p></div>

# Output

<div class="content"><p><span style="font-size: medium">* 第一行: 最后一天卖掉股票之后最多可能的钱数。 </span></p></div>

# Sample Input

<div class="content"><span class="sampledata">2 3 10<br/>
10 15 15<br/>
13 11 20<br/>
<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">24</span></div>

# Hint

<div class="content"><p></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Gold">Gold</a></p></div>

