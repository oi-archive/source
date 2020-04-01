
# Description

<div class="content">最近lxhgww又迷上了投资股票，通过一段时间的观察和学习，他总结出了股票行情的一些规律。
通过一段时间的观察，lxhgww预测到了未来T天内某只股票的走势，第i天的股票买入价为每股APi，第i天的股票卖出价为每股BPi（数据保证对于每个i，都有APi&gt;=BPi），但是每天不能无限制地交易，于是股票交易所规定第i天的一次买入至多只能购买ASi股，一次卖出至多只能卖出BSi股。
另外，股票交易所还制定了两个规定。为了避免大家疯狂交易，股票交易所规定在两次交易（某一天的买入或者卖出均算是一次交易）之间，至少要间隔W天，也就是说如果在第i天发生了交易，那么从第i+1天到第i+W天，均不能发生交易。同时，为了避免垄断，股票交易所还规定在任何时间，一个人的手里的股票数不能超过MaxP。
在第1天之前，lxhgww手里有一大笔钱（可以认为钱的数目无限），但是没有任何股票，当然，T天以后，lxhgww想要赚到最多的钱，聪明的程序员们，你们能帮助他吗？
</div>

# Input

<div class="content">输入数据第一行包括3个整数，分别是T，MaxP，W。
接下来T行，第i行代表第i-1天的股票走势，每行4个整数，分别表示APi，BPi，ASi，BSi。
</div>

# Output

<div class="content">输出数据为一行，包括1个数字，表示lxhgww能赚到的最多的钱数。

</div>

# Sample Input

<div class="content"><span class="sampledata">5 2 0<br/>
2 1 1 1<br/>
2 1 1 1<br/>
3 2 1 1<br/>
4 3 1 1<br/>
5 4 1 1<br/>
</span></div>

# Sample Output

<div class="content"><span class="sampledata">3<br/>
</span></div>

# Hint

<div class="content"><p>对于30%的数据，0 &lt; =W<t <="50,1" <="MaxP" <="50&lt;br">
   对于50%的数据，0 &lt; =W<t <="2000,1" <="MaxP" <="50&lt;br">
   对于100%的数据，0 &lt; =W<t <="2000,1" <="MaxP" <="2000&lt;br">
<br/>
   对于所有的数据，1 &lt; =BPi &lt; =APi &lt; =1000,1 &lt; =ASi,BSi &lt; =MaxP<br/>
<br/>
</t></t></t></p></div>

# Source

<div class="content"><p><a href="problemset.php?search=Day1">Day1</a></p></div>

